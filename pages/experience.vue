<template>
  <div class="experience-container">
    <div>
      <h1 style="text-align: center;">Experience page</h1>
      <Card
        title="Verizon"
        location="Full Stack Web Developer"
        year="March 2019
      – Nov 2019"
        content="Enhance user experience across multiple SMS channels
      with Bot messges. Working with NodeJS project creating rest API and
      working with Live Person API for Video and Voice calls."
        tagstring="NodeJs,ReactJs,JavaScript,AWS,MySQL"
      />
      <Card
        title="Verizon"
        location="Front End Web Developer"
        year="March 2019 – Nov 2019"
        content="Created ReactJS project from scratch with all webpack config to work with spring boot
application. Migrated Current Angular project to React JS and Helped maintaining legacy Angular Project"
        tagstring="AngularJs,ReactJs,JavaScript,Java, Spring Boot"
      />
      <Card
        title="VIRANI JEWELERS, INC"
        location="Graphics Designer"
        year="March 2018 - March 2019"
        content="Responsible for high-end photo retouching, Social media graphics design, Designing marketing materials and writing mailchimp email template."
        tagstring="ReactJs,JavaScript,GraphQL,Photoshop, Illustrator"
      />
      <Card
        title="Marketing Strategies & Solutions"
        location="Full Stack Web Developer"
        year="June 2015 – November 2017"
        content="Responsible for participating in the full life cycle of new website development projects, for implementing and maintaining best practice procedures in all areas of work. Developed dynamic web site using PHP, MySQL, HTML, CSS and JavaScript"
        tagstring="PHP, JavaScript, HTML5, CSS3, Wordpress, Photoshop, Illustrator, InDesign"
      />
      <Card
        title="Fanshawe College"
        location="Peer Tutor"
        year="May 2014 – Febuary 2016"
        content="Facilitated a learning environment for one-on-one tutoring, providing students with study techniques that resulted in improved academic performance"
        tagstring="PHP, Wordpress, .Net, Java, MySQL, JavaScript"
      />
      <Card
        title="Whyte Online"
        location="Joomla Developer"
        year="January 2014 – January 2015"
        content="Implementimg UX/UI designs into website for better user experience. Developing Joomla based websites"
        tagstring="PHP, Joomla, HTML, CSS, JavaScript"
      />
    </div>
  </div>
</template>

<script>
import Card from '../components/Card';
export default {
  components: {
    Card,
  },
};
</script>
