<template>
  <div style="margin-bottom: 40px;">
    <h1>Hello!</h1>

    <div class="paragraph">
      <div>
        <p>I'm <strong>Adrián Blanco Costas</strong>, a <strong>Senior XR Developer at Invelon Technologies</strong> with 8+ years of experience. I build applications that connect immersive experiences with the services behind them, working across Unity and Unreal Engine for XR, Strapi for backends, and Vue for web frontends.</p>
        <p>My experience goes beyond individual platforms. I have extensive experience integrating Unity into native Android and iOS applications, as well as Flutter apps. I design systems for bespoke projects and take them from initial requirements through development, deployment, and ongoing operation, including infrastructure on AWS using EC2, S3, and Route 53.</p>
        <p>I'm comfortable in environments where requirements evolve and developers need to take ownership, learn quickly, and solve problems across the stack. I also support tender submissions by contributing to technical proposals, translating project requirements into practical technical approaches.</p>
        <p>Outside work, I explore new tools and build personal projects, including Roblox experiences. I enjoy understanding how technologies fit together and turning that understanding into products people can use.</p>
        <p>You can reach me at <a href="mailto:adriblanc92@gmail.com">adriblanc92@gmail.com</a> or <router-link to="/contact">through here</router-link>.</p>
      </div>
    </div>

    <div class="photo">
      <img :src="`/img/Yo5-CircleMask.png`" alt="Avatar of Kadrius" /> 
    </div>

    <div style="clear:both"></div>

  </div>
</template>

<style scoped>
.paragraph {
  max-width: 750px;
  margin-bottom: 20px;
  font-size: 90%;
}

.photo {
  margin-top: 50px;
  text-align: center;
}

@media only screen and (min-width: 620px){
  .paragraph {
    float: left;
  }

  .photo {
    float: left;
    padding: 10px;
    padding-left: 80px;
  }
}

</style>
