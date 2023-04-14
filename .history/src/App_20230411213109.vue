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
      <img src="./assets/gmail-logo-16.png" alt="google-icon" width="20px" height="20px">
      <!-- <img src="./assets/facebook-f.svg" alt="google-icon"> -->
      <i class="fa-brands fa-facebook-f" style="color: #1191ee;"></i>
    </div>
  </div>
</div>

</template>

<script setup>

</script>


<style scoped>
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
  border: 1px solid black;
  background-color: yellow;
  font-weight: bolder;
  display: flex;
  justify-content: end;
  align-items: end;
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
  padding: 5px;
  border-radius: 7px;

}

</style>
