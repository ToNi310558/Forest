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
</style>
