<template>
<div class="navigation">
<nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
  <button type="button" class="btn btn-none"   style="border: 1px solid;"> <strong>HUMANS OF<br> NEW YORK</strong></button>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarText" style="padding-left: 700px;">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
         <button type="button" class="btn btn-none"><strong>STORIES .</strong></button>
      
        </li>
        <li class="nav-item">
           <button type="button" class="btn btn-none"> <strong>COUNTRIES  . </strong></button>
        </li>
        <li class="nav-item">
        <button type="button" class="btn btn-none"> <strong>STORIES . </strong></button>
        </li>
        <li class="nav-item">
         <button type="button" class="btn btn-none"><strong>SHARE</strong></button>
        </li>
      </ul>
    </div>
  </div>
</nav>
</div>

    <div class="paragraph">
      <h2>HUMANS OF NEW YORK</h2>
      <h1 style="font-size: 100px;">Series</h1>
      <p style="font-size: 25px;">These stories focus one specific population, examining<br> their experiences and the challenges that their face</p>
    </div>

    <div class="section1">
          <h3>HUMANS OF NEW YORK</h3>
          <h1 class="content1">Invisible<br> Wounds</h1>
           <button type="button" class="btn btn-none" style="hover: black">READ SERIES</button>
    </div>
    

    <div class="section2">
          <h3>HUMANS OF NEW YORK</h3>
          <h1 class="content2">Pediatric<br> Cancer</h1>
           <button type="button" class="btn btn-none">READ SERIES</button>
    </div>
    

    <div class="section3">
          <h3>HUMANS OF NEW YORK</h3>
          <h1 class="content3">Inmate<br> Stories</h1>
            <button type="button" class="btn btn-none">READ SERIES</button>
    </div>

     <div class="section4">
          <h3>HUMANS OF NEW YORK</h3>
          <h1 class="content4">Syrian<br> Americans</h1>
            <button type="button" class="btn btn-none">READ SERIES</button>
    </div>

    <div class="section5">
          <h3>HUMANS OF NEW YORK</h3>
          <h1 class="content5">Refugee<br> Stories</h1>
            <button type="button" class="btn btn-none">READ SERIES</button>
    </div>

    <footer>
      <h1>MORE HUMANS OF NEW YORK</h1>
      <img src="@/assets/Face1.png" alt="" class="images">
      <img src="@/assets/Twi.png" alt="" class="images">
      <img src="@/assets/social1.png" alt="" class="images">
    </footer>
   


   
    
   
    
 
</template>

<style>

.navigation{
  border-bottom: solid black 1px;
}
.paragraph{
  text-align: center;
}

.section1 {
   background-image: url("@/assets/Image1.jpg");
      background-repeat: no-repeat;
        background-position: center;
        background-size: cover;
        padding: 100px;
        height: 630px;
        text-align: right;
        
       
      

        .content1{ 
        color: rgb(105, 52, 27);
            font-size: 100px;
            line-height: 100px;
           font-family: 'GT Sectra Display Light';
}

          
        
         

}

.section2 {
   background-image: url("@/assets/Image2.jpg");
    background-repeat: no-repeat;
   background-position: center;
   background-size: cover;
    padding: 100px;
    height: 630px;
    text-align: left;
    font-family: 'GT Sectra Display Light';
}

.content2{ 
      color: rgb(198, 106, 31);
      font-size: 100px;
      line-height: 100px;
    font-family: 'GT Sectra Display Light'
}

.section3 {
   background-image: url("@/assets/Image3.jpg");
   background-repeat: no-repeat;
   background-position: center;
   background-size: cover;
   padding: 100px;
   height: 630px;
   text-align: right;
   font-family: 'GT Sectra Display Light';
}

.content3{ 
      color: rgb(201, 231, 214);
      font-size: 100px;
      line-height: 100px;
      font-family: 'GT Sectra Display Light'
}
.section4 {
  background-image: url("@/assets/Image4.jpg");
   background-repeat: no-repeat;
   background-position: center;
   background-size: cover;
   height: 630px;
    padding: 100px;
    text-align: left;
    font-family: 'GT Sectra Display Light';
   
}

.content4{ 
    color: rgb(198, 106, 31);
    font-size: 100px;
    line-height: 100px;
    font-family: 'GT Sectra Display Light'
}

.section5 {
      background-image: url("@/assets/Image5.jpg");
      background-repeat: no-repeat;
      background-position: center;
      background-size: cover;
      padding: 100px;
      height: 630px;
      text-align: right;
      
      
}

.content5{ 
    font-family: 'GT Sectra Display Light';
    font-size: 100px;
      line-height: 100px;
}


.phrase{
  text-align: center;
  background-color: black;
  padding: 150px;
  color: white;
   font-family: 'GT Sectra Display Light';
}

footer{
  background-color: black;
   font-family: 'GT Sectra Display Light';
  text-align: center;
  padding: 100px;
  color: white;
}

.images{
  height: 50px;
  weight: 50px; 
}

</style>

