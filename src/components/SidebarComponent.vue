<template>
    <div class="sidebar">
        <img src="../../img/dc-logo.png" alt="">
        <ul class="links">
            <li><a href="#">characters</a></li>
            <li><a href="#">comics</a></li>
            <li><a href="#">movies</a></li>
            <li><a href="#">tv</a></li>
            <li><a href="#">games</a></li>
            <li><a href="#">collectibles</a></li>
            <li><a href="#">videos</a></li>
            <li><a href="#">fan</a></li>
            <li><a href="#">news</a></li>
            <li><a href="#">shop</a></li>
        </ul>
    </div>
</template>


  
<script>
  export default {
    name: 'SidebarComponent',
  }
</script>


  
<style scoped>
  .sidebar{
    max-height: 100px;
    max-width: 100%;
    background-color:white;
    display: flex;
  }
  ul{
    list-style: none;
    text-decoration: none;
  }

  .links{
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 2rem;
  }
</style>