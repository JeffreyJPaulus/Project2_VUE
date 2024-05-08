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
<div class="container text-center">    
<div class="row">
  <div class="col-sm-3 well">

  </div>
  <div class="col-sm-7">
    <div class="row">
      <div class="col-sm-12">
        <div class="panel panel-default text-left">
          <div class="panel-body">
            <p id= "Portfolio" contenteditable="false"><h2>Portfolio for Client Side Frameworks</h2></p> 
          </div>
        </div>
      </div>
    </div>
    
    <div class="row">
      <div class="col-sm-3">
        <div class="well">
         <p>Project1</p>
         <img src="https://stackblitz.com/storage/blobs/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBeXBhRFE9PSIsImV4cCI6bnVsbCwicHVyIjoiYmxvYl9pZCJ9fQ==--00790d2debf5317d65d832774da0be454abc9089/bootstrapLogo.jpg" class="img-circle" height="55" width="55" alt="Avatar">
        </div>
      </div>
      <div class="col-sm-9">
        <div class="well">
          <p>Project 1 details <a href="https://jeffreyjpaulus.github.io/Frameworks/Project1/index.html"
            target="_blank">  https://jeffreyjpaulus.github.io/Frameworks/Project1/index.html</a> </p>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-sm-3">
        <div class="well">
         <p>Project 2</p>
         <img src="https://stackblitz.com/storage/blobs/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBeWRhRFE9PSIsImV4cCI6bnVsbCwicHVyIjoiYmxvYl9pZCJ9fQ==--10dd1029284ea1f51e4fd0ff329aa2458db9b706/vueLogo.png" class="img-circle" height="55" width="55" alt="Avatar">
        </div>
      </div>
      <div class="col-sm-9">
        <div class="well">
          <p>Project 2 This vue site is project 2. <a href="https://vue3-app-8epxff.stackblitz.io/#Exp"
            target="_blank">  https://vue3-app-8epxff.stackblitz.io/#Exp</a>  </p>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-sm-3">
        <div class="well">
         <p>Project 3</p>
         <img src="https://stackblitz.com/storage/blobs/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBeVphRFE9PSIsImV4cCI6bnVsbCwicHVyIjoiYmxvYl9pZCJ9fQ==--840a26938fbf0a0bb814f7d4175b324ab009b28e/reactLogo.png" class="img-circle" height="55" width="55" alt="Avatar">
        </div>
      </div>
      <div class="col-sm-9">
        <div class="well">
          <p>Project 3 using React:  <a href="https://vitejsvitejkgu5l-h2yo--5173--34455753.local-credentialless.webcontainer.io"
            target="_blank">  https://vitejsvitejkgu5l-h2yo--5173--34455753.local-credentialless.webcontainer.io</a></p>
        </div>
      </div>
    </div>
    <div class="row">
    <div class="col-sm-3">
      <div class="well">
       <p>Project 4</p>
       <img src="https://stackblitz.com/storage/blobs/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBeWhhRFE9PSIsImV4cCI6bnVsbCwicHVyIjoiYmxvYl9pZCJ9fQ==--7c52faea89db15dfcda86a2fb7e6722950bcc7d3/phaserLogo.jpg" class="img-circle" height="55" width="55" alt="Avatar">
      </div>
    </div>
    <div class="col-sm-9">
      <div class="well">
        <p>Project 4 upcoming.</p>
      </div>
    </div>
  </div>
   
  </div>
  <div class="col-sm-2 well">
    
  </div>
</div>
</div>

</template>

<script>
export default {
  name: 'Comp3',
  props: {  }
}
</script>