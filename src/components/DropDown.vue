<template>
<ul id="nav"> 
    <li><a href="#">Home</a></li> 
    <li><a href="#">Sobre</a></li> 
    <li><a href="#">O que Fazemos?</a> 
      <ul> 
        <li><a href="#">Web Design</a></li> 
        <li><a href="#">Hospedagem</a></li> 
        <li><a href="#">SEO</a></li> 
        <li><a href="#">Sistemas</a></li> 
      </ul> 
    </li>
 
    <li class="display"><a href="#">Contato</a></li> 
  </ul>
</template>

<script>
export default {

}
</script>

<style>



  ul {
margin: 0;
padding: 0;
list-style: none;
width: 150px;
}

ul li {
position: relative;
}

li ul {
position: absolute;
left: 149px;
top: 0;
display: none;
}

 ul li a {
   display: block;
   text-decoration: none;
   color: #E2144A;
   background: #fff;
   padding: 5px;
   border: 1px solid #ccc; 
}
* html ul li { float: left; }
* html ul li a { height: 1%; }

li:hover ul { display: block; }


</style>