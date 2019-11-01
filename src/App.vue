<template>
  <div>
   <section class="hero is-large gradient-blue is-bold mh-800 ">
    <div class="columns mh-800 ">
      <div class="column is-7">
        <div class="hero-body">
          <div class="columns is-centered">
            <div class="column is-8  is-10-tablet">
              <div class="title has-text-white">
                WE SEE YOU
                <br>
                WE RECOGNISE YOU. 
                <br>
                WE WELCOME YOU.
                <br>
                <p class="subtitle pt-20 has-text-white">Players, Artists, Fans, Creators And 
                Companies In The Video Game Industry! 
                Secure Your Free VIP Spot And Exclusive 
                Perks On The Official Social Networking 
                Platform Built Just For Video Game Culture.</p>
              </div>
              <button class="button button-gradient is-rounded is-large">Reserve You Spot Now</button>
                <div class="mt-50 pb-20" >
                <div class="subtitle has-text-white">
                  <div class="absolute">
                    Don't let you friends miss out!
                   <br>
                  Share on social.
                  </div>
                  <div class="is-pulled-right">
                    <button class="button round ml-50">
                    <span class="icon is-small">
                      <i class="fab fa-facebook-f"></i>
                    </span>
                  </button>
                  <button class="button round ml-20">
                    <span class="icon is-small">
                      <i class="fab fa-twitter"></i>
                    </span>
                  </button>
                  <button class="button round ml-20">
                    <span class="icon is-small">
                      <i class="fab fa-twitch"></i>
                    </span>
                  </button>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="column is-hidden-touch">
        <div class=" full-width">
          <iframe class="full-width" src="https://www.youtube.com/embed/-HB2hh7XaP0" frameborder="0" allowfullscreen="allowfullscreen"></iframe>
        </div>
      </div>
    </div>
  </section>
  <div class="columns is-mobile is-centered is-vcentered pt-20">
    <div class="is-8">
      <img src="./assets/logos.png" width="600px" alt="">
    </div>
  </div>
  <div class=" has-text-centered container pt-20">
    <div >
     <p class="is-size-3 ">ExampleCompany is de first and only <br> social networkin platformto</p>
    </div>
  </div>
   <vs-tabs alignment="center">
      <vs-tab label="Instant Tournaments">
        <div class="columns is-centered">
          <div class="column is-6">
            <div class="columns">
              <div class="column is-6">
                <img src="./assets/pages.png" alt="">
              </div>
              <div class="column is-6">
                <h3 class="is-size-5 ">Lorem ipsum dolor sit</h3>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime eligendi fugit in quibusdam quaerat aliquam deleniti soluta nobis neque voluptatibus sequi totam quis maiores tempora, tenetur fugiat autem et? Ab.
              </div>
            </div>
          </div>
        </div>
      </vs-tab>
      <vs-tab label="Verified Profiles">
        <div>
        </div>
      </vs-tab>
      <vs-tab label="Video Game Archievement Recognition">
        <div>

        </div>
      </vs-tab>
      <vs-tab label="Racking & Reputation">
        <div>

        </div>
      </vs-tab>
    </vs-tabs>
    <div class=" has-text-centered pt-20">
      <div class=" is-size-3">FAQ</div>
    </div>
    <div class="columns is-centered">
      <div class="column is-6">
        <vs-collapse>
     <vs-collapse-item  icon-arrow="add_circle_outline">
       <div slot="header">
         How do i get an Oficial World Record?
       </div>
       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque rhoncus eros tortor, non fringilla lectus cursus et. Fusce vel nisi ante. Aliquam sit amet lectus pharetra, luctus mi sed, aliquet felis. Mauris a tortor viverra, ornare tellus in, consectetur leo.
        <br><br>
        Etiam nec nunc nec nisl luctus tincidunt efficitur vitae elit. Vestibulum iaculis nibh commodo neque ultrices lobortis. Cras magna massa, pretium vitae mattis varius, pharetra nec massa. Aliquam ac ex enim. Quisque consequat dui libero, vel blandit lorem porttitor sit amet. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Nullam sed lobortis nisl, quis eleifend metus.
     </vs-collapse-item>
     <vs-collapse-item icon-arrow="add_circle_outline">
       <div slot="header">
         What Types of Archievement Will You Track?
       </div>
     </vs-collapse-item>
     <vs-collapse-item icon-arrow="add_circle_outline">
       <div slot="header">
          How Can I Submit A World Record?
       </div>
     </vs-collapse-item>
     <vs-collapse-item icon-arrow="add_circle_outline">
       <div slot="header">
         What Make  EC The Authority?
       </div>
     </vs-collapse-item>
     <vs-collapse-item icon-arrow="add_circle_outline">
       <div slot="header">
         What Can I Expert Once EC Officially?
       </div>
     </vs-collapse-item>
     <vs-collapse-item icon-arrow="add_circle_outline">
       <div slot="header">
         Why Is This Free...What´s The Catch?
       </div>
     </vs-collapse-item>
     <vs-collapse-item icon-arrow="add_circle_outline">
       <div slot="header">
         Who´s Running The Joint?
       </div>
     </vs-collapse-item>
     <vs-collapse-item icon-arrow="add_circle_outline">
       <div slot="header">
         Do You Have Some Kind Of Ethos Or Mission Statement?
       </div>
     </vs-collapse-item>
     <vs-collapse-item icon-arrow="add_circle_outline">
       <div slot="header">
        What if´m Not A Gamer, Can I Still Join? 
       </div>
     </vs-collapse-item>
    </vs-collapse>
      </div>
    </div>
    <footer class="footer footer-banner">
      <div class="content has-text-centered">
        <p class="is-size-6 has-text-white">
         RESERVE YOU SPOT NOW
        </p>
        <p class="is-size-3 has-text-white">
         Limited to the first 10,000 reservations.  <br>
         Official launch estimated for October 2019
        </p>
        <div class="has-text-center">
          <button class="is-rounded button is-danger is-inverted">SIGN UP</button>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>

export default {
  name: 'app',
  data() {
    return {
    }
  }
}
</script>

<style lang="scss">
@import url('./assets/App.scss');
</style>
