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

<head>
<title>Project 2</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
<style>    
  /* Set black background color, white text and some padding */
  footer {
    background-color: #555;
    color: white;
    padding: 15px;
  }
  table{
    border-collapse:collapse;
    border:1px solid #FF0000;
    }
    
    table td{
    border:1px solid #FF0000;
    }
</style>
</head>

  <div id="app">
    <navBar1 />
    <aboutMe />
    <portfolio />
    <TFooter />
  </div>
</template>

<script>
import navBar1 from './components/navBar1.vue'
import aboutMe from './components/aboutMe.vue'
import portfolio from './components/portfolio.vue'
import TFooter from './components/TFooter.vue'

export default {
  name: 'App',
  components: {
    navBar1,
    aboutMe,
    portfolio,
    TFooter,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
