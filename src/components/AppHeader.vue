<script>
  export default {
      name: 'AppHeader'
  }
</script>

<template>
    <header class="container">
        <div>
            <img src="../assets/img/dc-logo.png">
        </div>
        <nav>
            <ul>
                <li>
                    <a href="#">CHARACTERS</a>
                </li>
                <li id="active">
                    <a href="#">COMICS</a>
                </li>
                <li>
                    <a href="#">MOVIES</a>
                </li>
                <li>
                    <a href="#">TV</a>
                </li>
                <li>
                    <a href="#">GAMES</a>
                </li>
                <li>
                    <a href="#">COLLECTIBLES</a>
                </li>
                <li>
                    <a href="#">VIDEOS</a>
                </li>
                <li>
                    <a href="#">FANS</a>
                </li>
                <li>
                    <a href="#">NEWS</a>
                </li>
                <li>
                    <a href="#">SHOP</a>
                </li>
            </ul>
        </nav>
    </header>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;

    header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        
        nav {
            display: contents;

            
            ul {
                display: flex;

                li {
                    height: 120px;
                    margin-left: 20px;
                    display: flex;
                    align-items: center;
                    position: relative;

                    &#active::after {
                        color: $brand-primary;
                        content: '';
                        width: 100%;
                        height: 7px;
                        background-color: $brand-primary;
                        position: absolute;
                        left: 0;
                        bottom: 0;
                    }

                    a {
                        color: rgb(94, 93, 93);
                        font-weight: bold;
                    }
                }
            }
        }
    }
</style>