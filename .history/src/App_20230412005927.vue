<template>
<div class="wrapper">
  <div class="navbar">
    <div class="left">
      <div class="logo">MR</div>
      <ul>
        <li>Vectors</li>
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
    <h1 class="title">Popular Pro Stock Vectors</h1>
    <p class="paragraph">
      High quality Vectors with warry-tree licening for <br>
      personal and commercial use.
    </p>
    <div class="input_card">
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

  <div class="card_content">
    <div class="main_card">
      <div class="image_and_text_space">
        <i class="fa-solid fa-circle-nodes"></i>Premium
      </div>
      <p><span style="text-transform: uppercase; font-weight: bolder; font-size: 2em;">D</span>og illustration</p>
      <p class="download">Download <i class="fa-solid fa-download"></i></p>
    </div>
    <div class="main_card">
      <div class="image_and_text_space2">
        <i class="fa-solid fa-circle-nodes"></i>Premium
      </div>
      <p><span style="text-transform: uppercase; font-weight: bolder; font-size: 2em;">D</span>og illustration</p>
      <p class="download">Download <i class="fa-solid fa-download"></i></p>
    </div>
    <div class="main_card">
      <div class="image_and_text_space3">
        <!-- <img src="./assets/154416(1).svg" width="209px" height="300px" alt=""> -->
        <i class="fa-solid fa-circle-nodes"></i>Premium
      </div>
      <p><span style="text-transform: uppercase; font-weight: bolder; font-size: 2em;">D</span>og illustration</p>
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
      Discover All <br
    </div>
    <div class="between">
      Next page <i class="fa-solid fa-arrow-right"></i>
    </div>
    <div class="end"></div>
  </div>
</div>




</template>

<script setup>

</script>


<style scoped>
.wrapper{
  height: 100vh;
  width: 90vw;
  margin:auto;
}
*{
  padding: 0px;
  margin: 0px;
  box-sizing: border-box;
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
}

/* Second composant */

.text_section{
  margin: 30px auto;
  text-align: center;
}
.title{
  margin-bottom: 20px;
}
.paragraph{
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

/* last component */
</style>
