<template>
  <div class="about">
    <h1>About</h1>
 <div id="one">
   <h2>Company</h2>
 
  <h3> About Us : Delite Software Technologies was started with the single-minded vision of providing premier IT services to the Healthcare Industry. It’s goal is to be a leading provider of key IT services in every aspect of Healthcare. We bring together all the various domains under one roof. The Healthcare sector has diverse, growning, comlex needs that need unique solutions. Delite Healthcare</h3>
    <div id="mySidenav" class="sidenav">
  <a href="#" id="about"> <span><< </span>About</a>
  <a href="#" id="blog"><span><< </span>Blog</a>
  <a href="#" id="projects"><span><<</span>Projects</a>
  <a href="#" id="contact"><span><< </span>Contact</a>
</div>
    </div>
  
    
 </div>

</template>
<style>
h1{
  background-color: blanchedalmond;
  width:155px;
  margin-left:-500px;
}
h2{
position:absolute;
margin-left:-300px;
color:white;
}
h3{
  text-align:left;
  color:white;
  padding: 65px;
  margin-left:-325px;
  background-color: blue;

}
#mySidenav a {
  position: absolute;
  right:-40px;
  transition: 0.6s;
  padding:14px;
  width: 100px;
  text-decoration: none;
  font-size: 20px;
  color: white;
  border-radius: 0 5px 5px 0;
  
  
}

#mySidenav a:hover {
  right:35px;
  }

#about {
  top: 160px;
  background-color: #4CAF50;
}

#blog {
  top: 211px;
  background-color: #2196F3;
}

#projects {
  top: 262px;
  background-color: #f44336;
}

#contact {
  top: 313px;
  background-color: #555
}

</style>
