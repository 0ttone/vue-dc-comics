<template>

      <header class="container">
            <div class="navbar">
                  <div class="logo">
                        <img src="../assets/dc-logo.png" alt="DC-logo"/>
                  </div>
                  <div class="menu">
                        <ul>
                              <li><a href="">CHARACTERS</a></li>
                              <li><a href="">COMICS</a></li>
                              <li><a href="">MOVIES</a></li>
                              <li><a href="">TV</a></li>
                              <li><a href="">GAMES</a></li>
                              <li><a href="">COLLECTIBLES</a></li>
                              <li><a href="">VIDEO</a></li>
                              <li><a href="">FANS</a></li>
                              <li><a href="">NEWS</a></li>
                              <li><a href="">SHOP</a></li>
                        </ul>
                  </div>
            </div>



      </header>
</template>

<script>
export default {
      name: 'Header',
}
</script>

<style scoped lang="scss">

header {
      height: 100px;
      padding: 12px 0;

}

.navbar{
      display: flex;
      align-items: center;
      justify-content: space-between;
            
            img{
                  height: 72px;
            }

            ul{
                  display: flex;
                        li{
                              a{
                                    color: black;
                                    font-weight: bold;
                                    font-family: 'Roboto Condensed', sans-serif;
                                    margin-left: 24px;
                                    padding-bottom: 24px;
                                     &:hover{
                                           color:#0282f9;
                                           border-bottom: 3px solid #0282f9;
                                     }
                              }
                        }

            }
}
</style>
