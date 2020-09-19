<template>
  <div class="container">
    <div class="home-details">
      <span class="greetings">Hi, I am</span>
      <h1>Jay Patel</h1>
      <TypeEffect />
      <span class="leading"
        >I like to design and build beautifully crafted Websites.</span
      >
      <div class="button">
        <nuxt-link to="/contact">
          Hire Me
        </nuxt-link>
      </div>
      <ul class="social">
        <li>
          <a href="https://www.facebook.com/jaypatel1203" target="_blank">
            <FacebookIcon />
          </a>
        </li>
        <li>
          <a href="https://www.instagram.com/jaypatel1203" target="_blank">
            <InstagramIcon />
          </a>
        </li>
        <li>
          <a href="https://github.com/jaypateldesigns" target="_blank">
            <GithubIcon />
          </a>
        </li>

        <li>
          <a
            href="https://www.linkedin.com/in/jay-patel-b4a45643/"
            target="_blank"
          >
            <LinkedinIcon />
          </a>
        </li>
      </ul>
    </div>
    <div class="home-hero-image">
      <img src="~/assets/images/jay-hero-image.png" />
    </div>
  </div>
</template>

<script>
import {
  FacebookIcon,
  GithubIcon,
  InstagramIcon,
  LinkedinIcon,
  // MailIcon,
} from 'vue-feather-icons';
import TypeEffect from '../components/TypeEffect';
export default {
  components: {
    TypeEffect,
    FacebookIcon,
    InstagramIcon,
    GithubIcon,
    LinkedinIcon,
    // MailIcon,
  },
};
</script>

<style>
.jpd-container {
  width: 100%;
}
</style>
