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
      <img src="" alt="google-icon">
      <img src="" alt="google-icon">
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
}

ul{
  list-style: none;
  display: flex;
  gap: 30px;
}
.more{
  font-weight: bolder;
  padding-right: 4;
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

</style>
