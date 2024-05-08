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
    <div class="well">
      <p><a href="#">My Profile</a></p>
      <img src="https://stackblitz.com/storage/blobs/redirect/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBNHdIRFE9PSIsImV4cCI6bnVsbCwicHVyIjoiYmxvYl9pZCJ9fQ==--010a47615740f9c67c3641341c04707f10c09d06/computer.jpg" alt="big data" width="80" height="80">
      
    </div>

    <div class="alert alert-success fade in">
      <a href="#" class="close" data-dismiss="alert" aria-label="close">×</a>
      <p><strong>About</strong></p>
      Field Service Engineer and Full Time Student at CWI
    </div>
    <p><a href="#About">About</a></p>
    <p><a href="#Exp">Work Experience</a></p>
    <p><a href="#School">School</a></p>
    <p><a href="#Contact">Contact</a></p>
    <p><a href="#Portfolio">Portfolio</a></p>
  </div>
  <div class="col-sm-7">
  
    <div class="row">
      <div class="col-sm-12">
        <div class="panel panel-default text-left">
          <div class="panel-body">
            <p contenteditable="false"><h1>This is the VUE Project #2</h1></p> 
          </div>
        </div>
      </div>
    </div>
    
    <div class="row">
      <div class="col-sm-3">
        <div class="well">
         <p id="About"><h2>About</h2></p>
         <img src="https://stackblitz.com/storage/blobs/redirect/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBNHNIRFE9PSIsImV4cCI6bnVsbCwicHVyIjoiYmxvYl9pZCJ9fQ==--6bc40615e3c1177f11057252cc6b0ca2f33ec49d/big_data.png"  class="img-circle" alt="big data" width="55" height="55">
        </div>
      </div>
      <div class="col-sm-9">
        <div class="well">
        <h2>About Jeffrey Paulus</h2>
        

        <p>
          My first experience's with coding hacking at Quick Basic on my first "laptop" which was old even then... an 
          <a href="https://en.wikipedia.org/wiki/Amstrad_PPC_512"
          target="_blank"> 
              Amstrad PPC512D.</a>  which was followed by a Mac Pascal class in Highschool.
              
        </p>
        <img src="https://stackblitz.com/storage/blobs/redirect/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBNG9IRFE9PSIsImV4cCI6bnVsbCwicHVyIjoiYmxvYl9pZCJ9fQ==--765a8346829c529e4bc081fe94c61710c65fe1ab/Amstrad_PPC512_open.jpg" alt="Wiki image of Amstrad">
        <p><br>
          
          After my preliminary programming experiences, I decided to pursue a degree not in programming but the hardware running the programs which included a semester 
          learning assembly code for a Motorola processor providing great insights into "firmware".
        </p><br>
        <p>
          After Graduating with an AAS degree in electronics and working in various hardware related roles, I added a BS Management degree to my resume which enabled me to 
          work with people at all levels of Micron.  As my current job evolves, I am finding more of a need for software development skills as most of the hardware I support is now overseas.  While some of my past experiences have allowed me to get this far, I am 
          finding gaps in my understanding and knowledge.
        </p><br>
        <p>
          This triggered my next step in my continuous learning journey at CWI where I am pursuing an  <span style="font-style: italic; font-weight: bold;"> AAS Degree in Software Development</span>. 
          The classes currently coming to an end this first semester have taught me HTML5\CSS web design as well as C# which was not only an introduction the language but also helped me grasp the concept of Object Oriented Programming.  
          I believe this alone will enable me to develop what I am currently tasked to do at work as well as enable me to fill more needed roles in the future.  I am looking forward to my next 
          classes learning additional lessons in other languages and new concepts, I am excited to continue this path towards the degree.
        </p><br>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-sm-3">
        <div class="well">
         <p id="Exp">Experience</p>
                  
         <img src="https://stackblitz.com/storage/blobs/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBdzlhRFE9PSIsImV4cCI6bnVsbCwicHVyIjoiYmxvYl9pZCJ9fQ==--490469b816e55b6fe765ae93610d8831e716e621/uswest.jpg" class="img-circle" height="55" width="55" alt="Avatar">
         
         <img src="https://stackblitz.com/storage/blobs/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBeEZhRFE9PSIsImV4cCI6bnVsbCwicHVyIjoiYmxvYl9pZCJ9fQ==--5f60430731febfbeb11803f72f5fb59a0f520c67/qualcomm.png" class="img-circle" height="55" width="55" alt="Avatar">     

         <img src="https://stackblitz.com/storage/blobs/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBeEJhRFE9PSIsImV4cCI6bnVsbCwicHVyIjoiYmxvYl9pZCJ9fQ==--7ccc0617c4e55b5d718d02b07946551edd815730/micron.png" class="img-circle" height="55" width="55" alt="Avatar">  

        </div>
      </div>
      <div class="col-sm-9">
        <div class="well">
        <h2>Work Experience:</h2>
        <p>
            <a href="https://en.wikipedia.org/wiki/US_West"><b>US West Phone Company (Phoenix, Arizona)</b></a> 
                as a <span style="font-style: italic;">Installation Technician</span> working in the Large Business and Government Services group. 
                My primary responsibility was installing phone lines up to the demarcation point in government buildings and the larger businesses in the Phoenix area.
                
        </p>
        <p>
            <a href="https://www.qualcomm.com/"><b>Qualcomm (La Jolla, California)</b></a> 
                as a <span style="font-style: italic;">Senior Lab Technician</span> performing lab work for the software engineering group.  
                This work consisted primarily of setting up equipment including "EEBS"(Early Entry Base Stations), cabling between the EEBS and lab benches, spectrum analyzers, test boards, and the PC. 
                to enable the software engineers to run simulations for their Cell Phone software\firmware development.  Additionally I was asked to repair Cell Base Station equipment as needed.
        </p>
        <p>
            <a href="https://www.micron.com/"><b>Micron Technology (Boise, ID)</b></a> 
            <ol>
                <li>(Previous)<span style="font-style: italic; font-weight: bold;"> RMA Technician: </span> working in the internal RMA group troubleshooting and 
                    repairing equipment that had failed at Micron's test sites.</li>
                <br>
                <li>(Previous) <span style="font-style: italic; font-weight: bold;">Quality Process Engineer: </span> I was responsible for the QMS Process at the Micron Boise MFG site as well as assisting in arranging Boise site audits (Internal and External).</li>
                <br>
                <li>(Current) <span style="font-style: italic; font-weight: bold;">Field Service Engineer: </span> I travel to HVM (High Volume Manufacturing) sites located in Singapore, Taiwan, 
                    Malaysia, China, and soon to be India supporting the same equipment I was repairing when I first started working at Micron but at a much higher level.
                    I am now responsible to understand how the sites use the equipment, how it is breaking, how it can be improved on.  This requires me to travel occasionally too the HVM sites
                    for hands on troubleshooting and investigation of issues but primarly I am hosting meetings with each site to review issues and remotely monitor performance and repair data to find 
                    issues to address design and process related problems impacting production.  As Micron has expanded over the years, the amount of data has grown requiring new solutions.  
                    To better manage this I created a Database and software to collect data for easier remote reporting.  Through this project I found gaps in my knowledge which prompted me to continue to my education at CWI for software development.</li>
            </ol>
                
        </p>
    
        <hr>
        <h2 id="School">Education:</h2>
            <table border="1">
                <caption>
                    "Continuous learning is the minimum requirement for success in any field." - Brian Tracy<br>
                    “You are always a student, never a master. You have to keep moving forward.” - Conrad Hall<br>
                    “The only true wisdom is in knowing you know nothing.” -Socrates
                </caption>
                <thead>
                    <tr><th colspan="4">Continuous Learning Journey</th></tr>
                </thead>
                <tbody>
                    <tr id="Titles"><td>School</td> <td>Location</td> <td>Degree</td> <td>Years</td></tr>
                    <tr><td>DeVry Institute of Technology</td><td>Phoenix, AZ</td><td>AAS Degree: Electronics	</td><td>1996 - 1998 </td></tr>
                    <tr><td>Micron University</td><td>Boise, ID</td><td>Multiple Non-Degree: SQL, Statistics(DOE,Data Analysis) + </td><td>Continuous Learning</td></tr>
                    <tr><td>University of Phoenix</td><td>Boise, ID</td> <td>BS Degree: Business Management </td> <td>2005-2008 </td></tr>
                    <tr><td>EDX-MIT</td><td>Online</td><td>Non-Degree: Intro to Python</td><td>2016 - 2016</td></tr>
                    <tr><td>CWI</td><td>Boise, ID</td> <td>AAS Degree: Software Development </td> <td>2023- 2025<sup>*</sup> </td></tr>
                    
                </tbody>
                
                
            </table>
            <sup>*</sup>Estimated
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-sm-3">
        <div class="well">
         <p id="Contact">Contact me</p>
         <img src="https://stackblitz.com/storage/blobs/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBeVZhRFE9PSIsImV4cCI6bnVsbCwicHVyIjoiYmxvYl9pZCJ9fQ==--5b104bc1d663f94b66d87a6752393dda632310d7/contactMe.png" class="img-circle" height="55" width="55" alt="Contact Me">
        </div>
      </div>
      <div class="col-sm-9">
        <div class="well">
          <p>

        
        <section class="border p-4 d-flex justify-content-center mb-4">
        <form id="form" class="text-center" style="width: 100%; max-width: 300px" @submit.prevent="validateForm">
          <h2>Contact Me</h2>
    
          <!-- Name input -->
          <MDBInput label="Name" v-model="nameCustomValidation" wrapperClass="mb-4" />
    
          <!-- Email input -->
          <MDBInput type="email" label="Email address" v-model="emailCustomValidation" wrapperClass="mb-4" />
    
          <!-- Subject input -->
          <MDBInput label="Subject" v-model="subjectCustomValidation" wrapperClass="mb-4" />
    
          <!-- Message input -->
          <MDBTextarea wrapperClass="mb-4" label="Message" v-model="messageCustomValidation" />
    
          <!-- Mail copy -->
          <MDBCheckbox label="Send me copy" v-model="copyCustomValidation" />
    
          <!-- Submit button -->
          <MDBBtn color="primary" block class="my-4" type="submit">Send</MDBBtn>
    
          <!-- Status message -->
          <div ref="statusRef"></div>
        </form>
      </section>
    </p>



        </div>
      </div>
    </div>     
  </div>
  <div class="col-sm-2 well">
    <div class="thumbnail">
      <p>Upcoming Events:</p>
      <img src="https://stackblitz.com/storage/blobs/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBeXRhRFE9PSIsImV4cCI6bnVsbCwicHVyIjoiYmxvYl9pZCJ9fQ==--1c2e67f200fb22bfe3216acf39877fb450d3bbcd/cwiLogo.jpg" alt="Paris" width="400" height="300">
      <p><strong>Next Semester</strong></p>
      <p>Fall 2024</p>
      <button class="btn btn-primary">CWI Class List</button>
    </div>      
  </div>
</div>
</div>


</template>

<script>
import {
  MDBInput,
  MDBTextarea,
  MDBBtn,
  MDBCheckbox
} from "mdb-vue-ui-kit";
import {
  ref
} from "vue";

export default {
  
  name: 'Comp2',
  props: {  },
 
  
  components: {
    MDBInput,
    MDBTextarea,
    MDBBtn,
  },
  setup() {
    const nameCustomValidation = ref("");
    const emailCustomValidation = ref("");
    const subjectCustomValidation = ref("");
    const messageCustomValidation = ref("");
    const copyCustomValidation = ref(false);
    const statusRef = ref(null);
    const checkValidation = () => {
      let isDataValid = true;
      let statusMessage = "";

      if (nameCustomValidation.value === "") {
        statusMessage += '<p class="note note-danger"><strong>Name</strong> cannot be empty</p>';
        isDataValid = false;
      }

      if (emailCustomValidation.value === "") {
        statusMessage += '<p class="note note-danger"><strong>Email</strong> cannot be empty</p>';
        isDataValid = false;
      } else {
        const re =
          /^(([^<>()[]\.,;:s@"]+(.[^<p>()[]\.,;:s@"]+)*)|(".+"))@(([[0-9]{1,3}.[0-9]{1,3}.[0-9]{1,3}.[0-9]{1,3}])|(([a-zA-Z-0-9]+.)+[a-zA-Z]{2,}))$/;

        if (!re.test(emailCustomValidation.value)) {
          statusMessage += '<p class="note note-danger"><strong>Email</strong> is invalid</p>';
          isDataValid = false;
        }
      }

      if (subjectCustomValidation.value === "") {
        statusMessage +=
          '<p class="note note-danger"><strong>Subject</strong> cannot be empty</p>';
        isDataValid = false;
      }
      if (messageCustomValidation.value === "") {
        statusMessage +=
          '<p class="note note-danger"><strong>Message</strong> cannot be empty</p>';
        isDataValid = false;
      }
      return {
        isDataValid,
        statusMessage
      };
    };

    const validateForm = (e) => {
      const {
        isDataValid,
        statusMessage
      } = checkValidation();

      if (!isDataValid) {
        statusRef.value.innerHTML = statusMessage;
        return;
      }

      statusRef.value.innerHTML = '<p class="note note-success">Sending...</p>';
      e.target.submit();
    };

    return {
      nameCustomValidation,
      emailCustomValidation,
      subjectCustomValidation,
      messageCustomValidation,
      statusRef,
      validateForm
    };
  },





}
</script>