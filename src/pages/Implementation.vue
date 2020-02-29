<template>

  <b-container>
        
     <div style="margin-top: 40px; margin-bottom: 40px; text-align: left ">
        <h1>{{'Implem1'|localize}} <span style="color: #e16262;" >Employee Concept</span></h1>
      </div>

        <b-row align-v="center">
                   
          <b-col class="md-6" style=" text-align: left;  " >
                 
     
                <h1><span style="color: #e16262;">Designing</span></h1>                

                <p>{{'Implem2'|localize}}</p>

          </b-col>

          <b-col  class="md-6" style=" margin: 10px; " >
            <img width="270px" src="../imgs/impl1.png">
          </b-col>          
          
        </b-row>

        <b-row align-v="center">

          <b-col  class="md-6" style=" margin: 10px; " >
            <img width="200px" src="../imgs/Mobile.png">
          </b-col>                     
          
          <b-col class="md-6" style=" text-align: left;  " >
                <h1><span style="color: #e16262;">Branding</span></h1>             

                <p>{{'Implem3'|localize}}</p>
          </b-col>
        </b-row>

        <b-row align-v="center">

          <b-col class="md-6" style=" text-align: left;  " >
            <h1><span style="color: #e16262;">Launch and maintenance</span></h1>             
            <p>{{'Implem4'|localize}}</p>
          </b-col>

          <b-col  class="md-6" style=" margin: 10px; " >
            <img width="400px" src="../imgs/feature2.png">
          </b-col>                     
        
        </b-row>

        </b-container>

</template>

<script>
import SiteLayout from '@/layouts/SiteLayout';
import localizeFilter from '@/filters/localize.filter'
export default {
  
}
</script>
