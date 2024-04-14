<script>
  export default {
      name: 'AppFooter'
  }
</script>

<template>
    <footer>
      <section class="top">
        <div class="container">
          <div class="footer-nav">
            <div>
              <ul>
                <h3>DC COMICS</h3>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
              </ul>
              <ul>
                <h3>SHOP</h3>
                <li>lorem</li>
                <li>lorem</li>
              </ul>
            </div>
            <div>
              <ul>
                <h3>DC</h3>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
              </ul>
            </div>
            <div>
              <ul>
                <h3>SITES</h3>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
              </ul>
            </div>
          </div>
        </div>
      </section>
      <section class="bottom">
        <div class="container">
          <div class="sign-up">
            <button>SIGN-UP NOW!</button>
          </div>
          <div class="follow-us">
            <ul>
              <h3>FOLLOW US</h3>
              <li><img src="../assets/img/footer-facebook.png"></li>
              <li><img src="../assets/img/footer-twitter.png"></li>
              <li><img src="../assets/img/footer-youtube.png"></li>
              <li><img src="../assets/img/footer-pinterest.png"></li>
              <li><img src="../assets/img/footer-periscope.png"></li>
            </ul>
          </div>
        </div>
      </section>
    </footer>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;

  .top {
    background-image: url('../assets/img/footer-bg.jpg');
  
    .container {
      background-image: url('../assets/img/dc-logo-bg.png');
      background-repeat: no-repeat;
      background-position: 100%;
      background-size: 40%;

      .footer-nav {
        padding: 30px 0;
        color: white;
        display: flex;

        ul {
          padding: 15px 50px 15px 0;

          h3 {
            padding-bottom: 10px;
          }

          li {
          color: gray;
        }
        }

      }
    }
  }

  .bottom {
    background-color: rgb(94, 93, 93);
    
    .container {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 0;

      button {
        background-color: transparent;
        color: white;
        padding: 8px;
        border-color: $brand-primary;
        cursor: pointer;
      }

      h3 {
        color: $brand-primary;
        padding-right: 15px;
        padding-top: 8px;
      }

      ul {
        display: flex;
        
        li {
          padding-left: 8px;
        }
      }
    }
  }

</style>