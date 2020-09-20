<template>
  <div class="app">
    <aside class="app-sidebar">
      <div class="app-sidebar-image">
        <img src="~/assets/images/jay-sidebar.jpg" />
      </div>
      <div class="app-sidebar-logo">
        <Logo />
      </div>
      <nav class="app-nav">
        <ul>
          <nuxt-link to="/">
            <li>
              <HomeIcon size="16" />
              <label>Home</label>
            </li>
          </nuxt-link>

          <nuxt-link to="/about">
            <li>
              <UserIcon size="16" />
              <label>About</label>
            </li>
          </nuxt-link>
          <nuxt-link to="/skills">
            <li>
              <TargetIcon size="16" />
              <label>Skills</label>
            </li>
          </nuxt-link>
          <nuxt-link to="/education">
            <li>
              <BookIcon size="16" />
              <label>Education</label>
            </li>
          </nuxt-link>
          <nuxt-link to="/experience">
            <li>
              <BriefcaseIcon size="16" />
              <label>Experience</label>
            </li>
          </nuxt-link>
          <nuxt-link to="/contact">
            <li>
              <MailIcon size="16" />
              <label>Contact</label>
            </li>
          </nuxt-link>
        </ul>
      </nav>
    </aside>
    <section class="app-content">
      <Nuxt />
    </section>
    <div class="app-mobile-logo">
      <Logo width="80" />
    </div>
  </div>
</template>

<script>
import {
  HomeIcon,
  UserIcon,
  MailIcon,
  BookIcon,
  BriefcaseIcon,
  TargetIcon,
} from 'vue-feather-icons';
import Logo from '../components/Logo';
export default {
  components: {
    Logo,
    HomeIcon,
    UserIcon,
    MailIcon,
    BookIcon,
    BriefcaseIcon,
    TargetIcon,
  },
};
</script>

<style></style>
