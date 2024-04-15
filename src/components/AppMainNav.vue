<script>
  export default {
      name: 'AppMainNav'
  }
</script>

<template>
    <section class="main-nav">
        <div class="container">
            <nav>
                <ul>
                    <li>
                        <a href="#">
                            <img src="../assets/img/buy-comics-digital-comics.png">
                            <h3>DIGITAL COMICS</h3>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../assets/img/buy-comics-merchandise.png">
                            <h3>DC MERCHANDISE</h3>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../assets/img/buy-comics-subscriptions.png">
                            <h3>SUBSCRIPTION</h3>  
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../assets/img/buy-comics-shop-locator.png">
                            <h3>COMIC SHOP LOCATOR</h3>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../assets/img/buy-dc-power-visa.svg">
                            <h3>DC POWER VISA</h3>
                        </a>
                    </li>
                </ul>
            </nav>
        </div>
    </section>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;

    .main-nav {
        background-color: $brand-primary;
        padding: 35px;

        ul {
            display: flex;
            justify-content: space-around;
            color: white;

            a {
                display: flex;
                align-items: center;

                img {
                    height: 50px;
                }

                h3 {
                    padding-left: 10px;
                    font-size: 16px;
                }
            }
        }
    }
</style>