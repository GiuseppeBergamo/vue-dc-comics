<template>
  <div id="jumbotron">
    <div class="container footer-link-container">
      <div class="footer-links" v-for="list in footerLinks" :key="list.title">
        <h4>{{ list.title }}</h4>
        <ul>
          <li v-for="link in list.links" :key="link.text"><a :href="link.url">{{ link.text }}</a></li>
        </ul>
      </div>
      
    </div>
  </div>
</template>

<script>
export default {
  name: 'FooterJumbotron',
  data() {
    return {
      footerLinks: [
        {
          title: 'DC COMICS',
          links: [
            {url: '#', text: 'Characters'},
            {url: '#', text: 'Comics'},
            {url: '#', text: 'Movies'},
            {url: '#', text: 'TV'},
            {url: '#', text: 'Games'},
            {url: '#', text: 'Videos'},
            {url: '#', text: 'News'}
          ]
        },
        {
          title: 'SHOP',
          links: [
            {url: '#', text: 'SHOP DC'},
            {url: '#', text: 'SHOP DC Collectibles'}
            
          ]
        },
        {
          title: 'DC',
          links: [
            {url: '#', text: 'Terms of use'},
            {url: '#', text: 'Privacy Policy (new)'},
            {url: '#', text: 'Ad Choises'},
            {url: '#', text: 'Advertising'},
            {url: '#', text: 'Jobs'},
            {url: '#', text: 'Subscriptions'},
            {url: '#', text: 'Talent Workshop'},
            {url: '#', text: 'CPSC Certificates'},
            {url: '#', text: 'Ratings'},
            {url: '#', text: 'Shop Help'},
            {url: '#', text: 'Contact Us'}
          ]
        },
        {
          title: 'SITES',
          links: [
            {url: '#', text: 'DC'},
            {url: '#', text: 'MAD Magazine'},
            {url: '#', text: 'DC Kids'},
            {url: '#', text: 'DC Universe'},
            {url: '#', text: 'DC Power Visa'},
          ]
        }
      ]
    }
  }
}
</script>

<style>
  #jumbotron {
    height: 500px;
    background-image: url(../assets/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
  }

  .footer-link-container{
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    flex-wrap: wrap;
    align-content: flex-start;
    background-image: url(../assets/img/dc-logo-bg.png);
    background-repeat: no-repeat;
    background-position: right;
  }
  
  .footer-links {
    width: 10%;
    color: white;
    margin-bottom: 20px;
    margin-top: 20px;
  }

  .footer-links h4 {
    margin-bottom: 15px;
    font-size: 1.5rem;
  }

  .footer-links a {
    color: white;
  }

</style>