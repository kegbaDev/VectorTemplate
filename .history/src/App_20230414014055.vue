<template>
<div class="wrapper">
  <div class="navbar">
    <div class="left bounce">
      <div class="logo">MR</div>
      <ul>
        <li>
          Vectors
          <div class="sous_menu">
            <ul class="liens">
              <li class="lien">Notre </li>
              <li class="lien"></li>
              <li class="lien"></li>
            </ul>
          </div>
        </li>
        <li>Photos</li>
        <li>PSD</li>
        <li>Video</li>
        <li><span class="more" >More</span><i class="fa-solid fa-caret-down"></i></li>
      </ul>
    </div>
    <div class="right">
      <div class="submit">
        <i class="fa-solid fa-plus"></i>
        Submit
      </div>
      <div class="logo_collection">
        <div class="logo_card">
          <img src="./assets/gmail-logo-16.png" alt="google-icon" width="15px" height="15px">
        </div>
        <div class="logo_card">
          <i class="fa-brands fa-facebook-f" style="color: #1191ee; width: 25px;height: 20px;"></i>
        </div>
      </div>
    </div>
  </div>


  <!-- Second component -->


  <div class="text_section">
    <h1 class="title slideInUp">Popular Pro Stock Vectors</h1>
    <p class="paragraph slideInUp">
      High quality Vectors with warry-tree licening for <br>
      personal and commercial use.
    </p>
    <div class="input_card slideInRight">
      <select name="" id="">
        <option value="value1">Vectors</option>
        <option value="value2">Vectors</option>
      </select>
      <input type="text" placeholder="Search vectors... ">
      <i class="fa-solid fa-magnifying-glass" style="color: grey; margin-right: 15px;"></i>
    </div>
  </div>

  <!-- Third component -->
  
  <div class="row">
    <div class="left-row">
      <ul>
        <li>Latest<sup style="color:orange">*</sup></li>
        <li>Popular</li>
      </ul>
      <span class="pipe">
        |
      </span>
      <ul>
        <li style="color:orange">Premium</li>
        <li style="color:blue">Free</li>
      </ul>
    </div>
    <div class="right-row">
      <i class="fa-solid fa-sliders"></i>
      <i class="fa-solid fa-file-lines"></i>
    </div>
  </div>

  <!-- Fourth component  -->

  <div class="card_content slideInUp">
    <div class="main_card">
      <div class="image_and_text_space">
        <i class="fa-solid fa-circle-nodes"></i>Premium
      </div>
      <p style="margin-bottom: 10px;"><span style="text-transform: uppercase; font-weight: bolder; font-size: 40px;">D</span>og illustration</p>
      <p class="download">Download <i class="fa-solid fa-download"></i></p>
    </div>
    <div class="main_card">
      <div class="image_and_text_space2">
        <i class="fa-solid fa-circle-nodes"></i>Premium
      </div>
      <p style="margin-bottom: 10px;"><span style="text-transform: uppercase; font-weight: bolder; font-size: 40px;">D</span>og illustration</p>
      <p class="download">Download <i class="fa-solid fa-download"></i></p>
    </div>
    <div class="main_card">
      <div class="image_and_text_space3">
        <!-- <img src="./assets/154416(1).svg" width="209px" height="300px" alt=""> -->
        <i class="fa-solid fa-circle-nodes"></i>Premium
      </div>
      <p style="margin-bottom: 10px;"><span style="text-transform: uppercase; font-weight: bolder; font-size: 40px;">D</span>og illustration</p>
      <p class="download">Download <i class="fa-solid fa-download"></i></p>
    </div>
    <!-- <div class="main_card">
      <div class="image_and_text_space">
        Premium
      </div>
      <p>Dog illustration</p>
      <p class="download">Download<i class="fa-solid fa-download"></i></p>
    </div>
    <div class="main_card">
      <div class="image_and_text_space">
        Premium
      </div>
      <p>Dog illustration</p>
      <p class="download">Download<i class="fa-solid fa-download"></i></p>
    </div> -->
  </div>

  <!-- Last component -->
  <div class="last_row">
    <div class="start">
      <div class="part">
        Discover All <br>
        Collections
      </div>
      <img src="./assets/imagesfinal.jpg" alt="" style="width: 80px; height: 40px;">
    </div>
    <div class="between">
      Next page <i class="fa-solid fa-arrow-right"></i>
    </div>
    <div class="end">
      Page/ 120
    </div>
  </div>
</div>




</template>

<script setup>

</script>


<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Arimo:wght@500&display=swap');
.wrapper{
  height: 100vh;
  width: 90vw;
  margin:auto;
}
*{
  padding: 0px;
  margin: 0px;
  box-sizing: border-box;
  /* font-family: 'Arimo', sans-serif; */
}
.left{
  display: flex;
  align-items: center;
}

ul{
  list-style: none;
  display: flex;
  gap: 30px;
  margin-left: 30px;
}
ul li{
  cursor: pointer;
}
.more{
  font-weight: bolder;
  padding-right: 4px;
}
.logo{
  width: 30px;
  height: 30px;
  border: 1px solid rgb(214, 201, 201);
  background-color: yellow;
  font-weight: bolder;
  display: flex;
  justify-content: end;
  align-items: end;
  border-radius: 3px;
  cursor: pointer;
}
.navbar{
  display: flex;
  justify-content: space-between;
}
.right{
  display: flex;
  gap: 3px;
}
.submit{
  border: 1px solid gray;
  padding: 7px;
  margin-right: 30px;
  border-radius: 5px;
  background-color: rgba(234, 233, 233, 0.03);
  cursor: pointer;
  transition: all 400ms ease-in-out;
}
.submit:hover{
  background-color: yellow;
  /* font-weight: bolder; */
  scale: 1.1;
}
.logo_collection{
  display: flex;
  gap: 10px;
}
.logo_card{
  width: 30px;
  height: 30px;
  border: 1px solid black;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 50%;
  border-color: rgb(202, 198, 198);
  -webkit-box-shadow: 0px 10px 13px -7px #000000, -2px -2px 15px 6px rgba(26,17,18,0); 
  box-shadow: 0px 10px 13px -7px #000000, -2px -2px 15px 6px rgba(26,17,18,0);
  cursor: pointer;transition: all 300ms ease-in-out;

}
.logo_card:hover{
  -webkit-box-shadow: 0px 10px 13px -7px #000000, -2px -2px 15px 6px rgba(26,17,18,0); 
  box-shadow: 0px 10px 13px -7px #000000, -2px -2px 15px 6px rgba(26,17,18,0);
  scale: 1.2;

}

/* Second composant */

.text_section{
  margin: 30px auto;
  text-align: center;
}
.title{
  font-family: 'Arimo', sans-serif;
  margin-bottom: 20px;
}
.paragraph{
  font-family: 'Arimo', sans-serif;
  margin-bottom: 20px;
  color: rgb(107, 106, 106);
}
.input_card{
  width: 60%;
  height: 50px;
  background-color: white;
  margin: auto;
  display: flex;
  align-items: center;
  border-radius: 2px;
}
input{
  width: 100%;
  padding-left: 20px;
  border: none;
}
input, select{
  height: 40px;
}
select{
  padding: 9px;
  margin-left: 7px;
}

/* Third component */
.row{
  display: flex;
  justify-content: space-between;
  margin-bottom: 20px;
}
.left-row ul{
  margin: 0px;
  padding: 0px;
  display: flex;
  align-items: center;
}
.left-row, .right-row{
  display: flex;
  align-items: center;
}
.pipe{
  margin: 0px 20px;
}

.pipe{
  font-weight: bolder;
  font-size: 1.3em;
}
.right-row{
  gap: 10px;
}

/* Fourth component */

.card_content{
  display: flex;
  justify-content: space-between;
}
.main_card{
  min-width: 370px;
  min-height: 350px;
  /* border: 1px solid black; */
  border-radius: 10px;
  background-color: white;
  box-shadow: rgba(50, 50, 93, 0.25) 0px 13px 27px -5px, rgba(0, 0, 0, 0.3) 0px 8px 16px -8px;
  padding-bottom: 25px;
  cursor: pointer;
  transition: all 400ms ease-in-out;
}
.main_card:hover{
  scale: 1.02;
}
.main_card p{
  text-align: center;
}
.download{
  font-weight: bolder;
  text-decoration: underline;
  font-size: large;
}
.image_and_text_space{
  padding-top: 6px;
  padding-right: 10px;
  text-align: end;
  height: 70%;
  width: 92%;
  border: 1px solid rgb(201, 199, 199);
  border-radius: 10px;
  margin: 15px auto;
  background-image: url(./assets/chien_color.jpg);
  background-repeat: no-repeat;
  background-position: center;
}
.image_and_text_space2{
  background-image: url(./assets/velo.jpg) !important;
  padding-top: 6px;
  padding-right: 10px;
  text-align: end;
  height: 70%;
  width: 92%;
  border: 1px solid rgb(201, 199, 199);
  border-radius: 10px;
  margin: 15px auto;
  background-repeat: no-repeat;
  background-position: center;
}
.image_and_text_space3{
  background-image: url(./assets/sa.webp) !important;
  padding-top: 6px;
  padding-right: 10px;
  text-align: end;
  height: 70%;
  width: 92%;
  border: 1px solid rgb(201, 199, 199);
  border-radius: 10px;
  margin: 15px auto;
  background-repeat: no-repeat;
  /* object-fit: contain; */
  background-position: center;
}

/* Animation */

.bounce {
  -webkit-animation-name: bounce;
  animation-name: bounce;
  -webkit-transform-origin: center bottom;
  -ms-transform-origin: center bottom;
  transform-origin: center bottom;
  -webkit-animation-duration: 1s;
  animation-duration: 1s;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
  }
  @-webkit-keyframes bounce {
  0%, 20%, 53%, 80%, 100% {
  -webkit-transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
  transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
  -webkit-transform: translate3d(0,0,0);
  transform: translate3d(0,0,0);
  }
  40%, 43% {
  -webkit-transition-timing-function: cubic-bezier(0.755, 0.050, 0.855, 0.060);
  transition-timing-function: cubic-bezier(0.755, 0.050, 0.855, 0.060);
  -webkit-transform: translate3d(0, -30px, 0);
  transform: translate3d(0, -30px, 0);
  }
  70% {
  -webkit-transition-timing-function: cubic-bezier(0.755, 0.050, 0.855, 0.060);
  transition-timing-function: cubic-bezier(0.755, 0.050, 0.855, 0.060);
  -webkit-transform: translate3d(0, -15px, 0);
  transform: translate3d(0, -15px, 0);
  }
  90% {
  -webkit-transform: translate3d(0,-4px,0);
  transform: translate3d(0,-4px,0);
  }
  }
  
  @keyframes bounce {
  0%, 20%, 53%, 80%, 100% {
  -webkit-transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
  transition-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1.000);
  -webkit-transform: translate3d(0,0,0);
  transform: translate3d(0,0,0);
  }
  40%, 43% {
  -webkit-transition-timing-function: cubic-bezier(0.755, 0.050, 0.855, 0.060);
  transition-timing-function: cubic-bezier(0.755, 0.050, 0.855, 0.060);
  -webkit-transform: translate3d(0, -30px, 0);
  transform: translate3d(0, -30px, 0);
  }
  70% {
  -webkit-transition-timing-function: cubic-bezier(0.755, 0.050, 0.855, 0.060);
  transition-timing-function: cubic-bezier(0.755, 0.050, 0.855, 0.060);
  -webkit-transform: translate3d(0, -15px, 0);
  transform: translate3d(0, -15px, 0);
  }
  90% { -webkit-transform: translate3d(0,-4px,0); transform: translate3d(0,-4px,0);
  }
} 
.slideInUp {
  -webkit-animation-name: slideInUp;
  animation-name: slideInUp;
  -webkit-animation-duration: 1s;
  animation-duration: 1s;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
  }
  @-webkit-keyframes slideInUp {
  0% {
  -webkit-transform: translateY(100%);
  transform: translateY(100%);
  visibility: visible;
  }
  100% {
  -webkit-transform: translateY(0);
  transform: translateY(0);
  }
  }
  @keyframes slideInUp {
  0% {
  -webkit-transform: translateY(100%);
  transform: translateY(100%);
  visibility: visible;
  }
  100% {
  -webkit-transform: translateY(0);
  transform: translateY(0);
  }
} 

.slideInRight {
  -webkit-animation-name: slideInRight;
  animation-name: slideInRight;
  -webkit-animation-duration: 1s;
  animation-duration: 1s;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
  }
  @-webkit-keyframes slideInRight {
  0% {
  -webkit-transform: translateX(100%);
  transform: translateX(100%);
  visibility: visible;
  }
  100% {
  -webkit-transform: translateX(0);
  transform: translateX(0);
  }
  }
  @keyframes slideInRight {
  0% {
  -webkit-transform: translateX(100%);
  transform: translateX(100%);
  visibility: visible;
  }
  100% {
  -webkit-transform: translateX(0);
  transform: translateX(0);
  }
  } 

.slideInUp {
  -webkit-animation-name: slideInUp;
  animation-name: slideInUp;
  -webkit-animation-duration: 1s;
  animation-duration: 1s;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
  }
  @-webkit-keyframes slideInUp {
  0% {
  -webkit-transform: translateY(100%);
  transform: translateY(100%);
  visibility: visible;
  }
  100% {
  -webkit-transform: translateY(0);
  transform: translateY(0);
  }
  }
  @keyframes slideInUp {
  0% {
  -webkit-transform: translateY(100%);
  transform: translateY(100%);
  visibility: visible;
  }
  100% {
  -webkit-transform: translateY(0);
  transform: translateY(0);
  }
} 

/* Animation */

/* last component */

.last_row{
  margin-top: 40px;
  margin-bottom: 40px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.between{
  font-weight: bolder;
  padding: 0px 20px;
  background-color: white;
  border-radius: 5px;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 5px;
}
.start{
  display: flex;
  align-items: center;
  gap: 3px;
  text-decoration: underline;
  font-weight: bold;
}
</style>
