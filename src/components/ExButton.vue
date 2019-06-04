
<template>
    <div class="ExBtn">
        <a href="#">
            <div class="shape">
                <button class="btn">Button</button>
            </div>
        </a>
        <a href="#">
            <div class="shape">
                 <p><font-awesome-icon :icon="['fab', 'gratipay']" /></p>
            </div>
        </a>
    </div>
</template>
<style scoped>
.shape
{
    background: #F6F6F6;
    width: 300px;
    height: 150px;
    text-align: center;
    margin: auto;
    margin-bottom: 50px;
   
}
.shape:hover {
 	box-shadow: 0 5px 5px gray; 
    transition: all 0.2s linear;
	transform: scale(1.01,1.01);
}
 			
.btn {
  background-color: rgb(66, 64, 230); 
  border: none;
  color: white;
  font-weight: bold;
  padding: 15px 30px;
  text-align: center;
  text-decoration: none;
  cursor: pointer;
  font-size: 16px;
  margin: 50px;
  border-radius: 5px;
}
p {
    font-size:40px;
    line-height: 150px;
}
</style>

