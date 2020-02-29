<template>

  <b-container style="max-width: 1650px">
        
     <div style="margin-top: 40px; margin-bottom: 40px; text-align: left ">
        <h1><span style="color: #e16262;">Employee Concept </span>{{'func_oport'|localize}} </h1>
      </div>
      <div style="margin: 40px; text-align: left; text-size: ">
        <p>{{"FunctionPage0"|localize}}</p>
      </div>

        <b-row align-v="center">
                   <!-- 1 -->
          <b-col class="md-3" style=" min-height:550px " >
                <h1>{{"FunctionPage1"|localize}}</h1>
                 <img width="270px" src="../imgs/1DayC.png">

                 <b-card  >
                   <p>{{"FunctionPage2"|localize}}</p>
                </b-card>
          </b-col>
            <!-- 2 -->
          <b-col  class="md-3" style=" min-height:550px " >
                <h1>{{"FunctionPage3"|localize}}</h1>
                 <img width="270px" src="../imgs/TrainingC.png">

                 <b-card>
                   <p>{{"FunctionPage4"|localize}}</p>
                </b-card>
          </b-col>
          
          <!-- 3 -->
           <b-col class="md-3" style=" min-height:550px  " >
                <h1>{{"FunctionPage5"|localize}}</h1>
                 <img width="270px" src="../imgs/TestC.png">
                 <b-card >
                   <p>{{"FunctionPage6"|localize}}</p>
                </b-card>
          </b-col>
          <!-- 4 -->
          <b-col class="md-3" style=" min-height:550px  " >
                <h1>{{"FunctionPage9"|localize}}</h1>
                 <img width="270px" src="../imgs/PrintDocuC.png">
                 <b-card >
                   <p>{{"FunctionPage10"|localize}}</p>
                </b-card>
          </b-col>
        <!-- 5 -->
          <b-col class="md-3" style=" min-height:550px  " >
                <h1>{{"FunctionPage7"|localize}}</h1>
                 <img width="270px" src="../imgs/Rating.png">
                 <b-card >
                   <p>{{"FunctionPage8"|localize}}</p>
                </b-card>
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
