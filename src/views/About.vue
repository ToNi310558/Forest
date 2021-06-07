<template>
  <div>
    <div class="about">
    <h2>Your content</h2>
      <div class="flex">
        <p class="about-info ai-black">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Amet autem eveniet, exercitationem fugit, ipsa ipsam
          iusto magni nemo non nostrum quasi qui quisquam reiciendis repellendus temporibus voluptates voluptatum. A ab
          accusantium adipisci amet asperiores aspernatur assumenda autem beatae commodi consectetur cumque cupiditate
          dolores doloribus ducimus eligendi enim ex exercitationem facilis fugiat harum illo itaque, libero modi mollitia
          non nostrum odio officia pariatur perspiciatis reprehenderit repudiandae sit soluta sunt tempore temporibus vitae
          voluptas! Facere facilis iusto quo repellendus sunt. Earum molestiae repellendus vel.
          Commodi dolores eaque facere facilis molestias placeat, quaerat saepe sint sunt voluptatibus! Eaque et ipsum odio
          praesentium voluptates?</p>
        <p class="about-info ai-white">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Amet autem eveniet, exercitationem fugit, ipsa ipsam
          iusto magni nemo non nostrum quasi qui quisquam reiciendis repellendus temporibus voluptates voluptatum. A ab
          accusantium adipisci amet asperiores aspernatur assumenda autem beatae commodi consectetur cumque cupiditate
          dolores doloribus ducimus eligendi enim ex exercitationem facilis fugiat harum illo itaque, libero modi mollitia
          non nostrum odio officia pariatur perspiciatis reprehenderit repudiandae sit soluta sunt tempore temporibus vitae
          voluptas! Facere facilis iusto quo repellendus sunt. Earum molestiae repellendus vel.
          Commodi dolores eaque facere facilis molestias placeat, quaerat saepe sint sunt voluptatibus! Eaque et ipsum odio
          praesentium voluptates?</p>
      </div>
  </div>
    <Footer/>
  </div>
</template>

<script>
import Footer from '../components/Footer'
export default {
  name: 'About',
  components: { Footer }
}
</script>

<style>
  .about{
    text-align: center;
    color: white;
    margin-bottom: 200px;
  }
  h2{
    text-transform: uppercase;
    font-size: 60px;
    margin-top: 0;
    margin-bottom: 44px;
  }
  .about-info{
    width: 700px;
    font-size: 24px;
    margin-top: 180px;
  }
  .flex{
    display: flex;
    justify-content: space-around;
  }
  .ai-black{
    color: black;
    background: rgba(255, 255, 255, 0.5);
    border-radius: 20px;
  }
  .ai-white{
    background: rgba(0, 0, 0, 0.5);
    border-radius: 20px;
  }
  @media only screen and (min-width: 1279px) and (max-width: 1439px){
    .about{
      margin-bottom: 226px;
    }
    h2{
      font-size: 46px;
      margin-bottom: 50px;
    }
    .about-info{
      width: 540px;
      font-size: 20px;
      margin-top: 200px;
    }
  }
  @media screen and (min-width: 1024px) and (max-width: 1279px){
    .about{
      margin-bottom: 280px;
    }
    h2{
      font-size: 32px;
      margin-bottom: 120px;
    }
    .about-info{
      width: 450px;
      font-size: 22px;
      margin-top: 180px;
    }
  }
  @media screen and (min-width: 800px) and (max-width: 1023px){
    .about{
      margin-bottom: 240px;
    }
    h2{
      font-size: 24px;
      margin-bottom: 100px;
    }
    .about-info{
      width: 370px;
      font-size: 20px;
      margin-top: 160px;
    }
  }
  @media screen and (min-width: 640px) and (max-width: 799px){
    .about{
      margin-bottom: 220px;
    }
    h2{
      font-size: 22px;
      margin-bottom: 100px;
    }
    .about-info{
      width: 310px;
      font-size: 17px;
      margin-top: 130px;
    }
  }
</style>
