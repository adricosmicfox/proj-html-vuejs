
<template>
  <header class="d-flex justify-content-between align-items-center">
    <div>
        <img src="../assets/dark-logo.png" alt="logo max coach">
    </div>

    <div class="d-flex">
        <ul class="d-flex justify-content-between align-items-center">
            <li>Home <img class="am-arrow-icon" src="../assets/arrow-list.svg" alt=""></li>
            <li>Pages <img class="am-arrow-icon" src="../assets/arrow-list.svg" alt=""></li>
            <li>Courses <img class="am-arrow-icon" src="../assets/arrow-list.svg" alt=""></li>
            <li>Features <img class="am-arrow-icon" src="../assets/arrow-list.svg" alt=""></li>
            <li>Blog <img class="am-arrow-icon" src="../assets/arrow-list.svg" alt=""></li>
            <li>Shop <img class="am-arrow-icon" src="../assets/arrow-list.svg" alt=""></li>
            <img class="am-cart-icon" src="../assets/cart3.svg" alt="">
            <img 
           class="am-user-icon" src="../assets/person-circle.svg" alt="">
            </ul>

            <div class="am-search-box d-flex"> 
                <input type="text" placeholder="Search..."> 
                <img class="am-search-icon" src="../assets/search.svg" alt="">
            </div>

            
    </div>
  </header>
</template>


<!-- *****JAVSCRIPT***** -->
<script>
export default {
name: 'HeaderComponent'
}
</script>



<!-- *****CSS STYLE***** -->
<style lang="scss" scoped>
@import "../style/common.scss";

header{
    width: 100%;
    height: 5rem;
    background-color: #E9E6E3;
    padding-left: 17rem;
    padding-right: 17rem;
    position: fixed;
    z-index: 999;

    img{
        width: 12rem;
    }

    ul{
        list-style: none;
        margin: 0;
        width: 40rem;
    }

    li{
        color: $primary;
        
    }

    input{
        border: none;
        
    }

    .am-search-box{
        background-color: white;
        border-radius: 7px;
        padding: .5rem;
            }
    .am-arrow-icon{
        width: .6rem;
    }

    .am-cart-icon{
        width: 1.3rem;
        filter: invert(24%) sepia(9%) saturate(2529%) hue-rotate(236deg) brightness(85%) contrast(82%);        
     }

    .am-user-icon{
        width: 1.3rem;
        margin-right: 1rem;
        filter: invert(24%) sepia(9%) saturate(2529%) hue-rotate(236deg) brightness(85%) contrast(82%);
    }

    .am-search-icon{
        width: 1.2rem;
        filter: invert(55%) sepia(79%) saturate(415%) hue-rotate(121deg) brightness(88%) contrast(89%);
    }
}



</style>