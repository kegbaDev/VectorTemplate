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
</div>
</template>

<script>

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

</style>