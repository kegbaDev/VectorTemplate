<template>


</template>


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
