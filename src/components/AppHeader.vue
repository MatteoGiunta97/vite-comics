<script>
  export default {
      name: 'AppHeader'
  }
</script>

<template>
    <header>
        <div>
            <img src="../assets/img/dc-logo.png">
        </div>
        <nav>
            <ul>
                <li>
                    <a href="#">CHARACTERS</a>
                </li>
                <li>
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
    header {
        max-height: 150px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 10px 20px;

        nav {
          
            ul {
            display: flex;
            list-style: none;

                li {
                    margin-left: 15px;

                    a {
                    text-decoration: none;
                    color: black;
                    font-weight: bold;
                    }
                }
            }
        }
    }
</style>