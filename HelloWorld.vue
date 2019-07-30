<template>
<div id="one">
  <div class="container">
  
  <div class="overlay">
  
  
  </div>
</div>
  </div> 
  


        
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.container {
  position: relative;
  background-image:url("desktop3.png");
  width:600px;
  max-width: 1000px;
  height:450px;
}

.image {
  display: block;
  width: 100%;
  height: auto;
}

.overlay {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  height: 100%;
  width: 100%;
  opacity: 0;
  transition: .3s ease;
  background-image:url("salesforce.png");


}

.container:hover .overlay {
  opacity: 1;
  transform: rotate(20deg);
}

.icon {
  color: white;
  font-size: 100px;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  text-align: center;
}

.fa-user:hover {
  color: #eee;
}







#container
{
 background-color: rgb(51, 12, 12);
  width: 1300px;
  height:300px;
  padding: 50px;
  margin-left:-557px;
}
#one
{
background-image:url("");
}
#one:hover
{
-webkit-transition:rotateY(250deg);
transition:rotateY(360deg);
transition-delay: 0s;  

}
</style>
