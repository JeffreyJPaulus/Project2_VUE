<!------------------------------------------------------------------------
#Original Author: Jeffrey Paulus                                         #
#Date Created: 4-21-24                                                   #
#Version: 0.2                                                            #
#Date Last Modified: 5-6-24                                              #
#Modified by: Jeffrey Paulus                                             #
#Modification log:                                                       #
#--Version 0.1 - 4-21-24 - Created for Project 2 and W5 Vue Homework     #
#--Version 0.2 - 5-6-24 - Updated for Project 2                          #
-------------------------------------------------------------------------->

<template>




<!DOCTYPE html>
<html lang="en">

<body>

<nav class="navbar navbar-inverse">
  <div class="container-fluid">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>                        
      </button>
      <a class="navbar-brand" href="#">Jeffrey Paulus</a>
    </div>
    <div class="collapse navbar-collapse" id="myNavbar">
      <ul class="nav navbar-nav">
        <li class="active"><a href="#">Home</a></li>
        <li><a href="#About">About</a></li>
        <li><a href="#Exp">Work Experience</a></li>
        <li><a href="#School">School</a></li>
        <li><a href="#Contact">Contact</a></li>
        <li><a href="#Portfolio">Portfolio</a></li>

      </ul>
     
    </div>
  </div>
</nav>
  

</body>
</html>









































</template>

<script>
export default {
  name: 'navBar1',
  props: {  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
