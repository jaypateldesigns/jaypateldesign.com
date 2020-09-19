<template>
  <div class="contact-container">
    <div>
      <h1 style="text-align: center;">Contact page</h1>
      <form class="contact-form" @submit.prevent="sendEmail">
        <div v-if="isSuccess" class="success">
          <span
            >Thank you for contacting me. I will reach out to you as soon as
            possible</span
          >
        </div>
        <div v-if="isError" class="error">
          <span
            >Sorry! there is trouble reaching to me. Please try after some
            time</span
          >
        </div>
        <label>Name</label>
        <input type="text" name="user_name" />
        <label>Email</label>
        <input type="email" name="user_email" />
        <label>Message</label>
        <textarea name="message"></textarea>
        <input type="submit" class="button" value="Send" />
      </form>
    </div>
  </div>
</template>

<script>
import emailjs from 'emailjs-com';

export default {
  name: 'Contact',
  data: () => ({
    isSuccess: false,
    isError: false,
  }),
  methods: {
    sendEmail(e) {
      emailjs
        .sendForm(
          'service_w5d2rs2',
          'template_bzcv8jt',
          e.target,
          'user_eiLjfB3BIARloKEpBXZh2'
        )
        .then(
          (result) => {
            if (result.status === 200 && result.text === 'OK') {
              this.$set(this, 'isSuccess', true);
            } else {
              this.$set(this, 'isError', true);
            }
          },
          (error) => {
            if (error) {
              this.$set(this, 'isError', true);
            }
          }
        );
    },
  },
};
</script>
