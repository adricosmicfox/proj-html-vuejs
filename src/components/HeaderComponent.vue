
<template>
  <header class="d-flex justify-content-between align-items-center">
    <div>
        <img class="img-fluid" src="../assets/dark-logo.png" alt="logo max coach">
    </div>

    <div class="d-flex">
        <ul class="d-flex">
            <li>Home</li>
            <li>Pages</li>
            <li>Courses</li>
            <li>Features</li>
            <li>Blog</li>
            <li>Shop</li>
            </ul>

            <input type="text" placeholder="   Search...">
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
header{
    width: 100%;
    height: 6rem;
    background-color: #E9E6E3;
    padding-left: 17rem;
    padding-right: 17rem;

    img{
        width: 12rem;
    }

    ul{
        list-style: none;
        margin: 0;
    }

    li{
        
    }
}



</style>