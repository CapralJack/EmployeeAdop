<template>

  <b-container>
        
     <div style="margin-top: 40px; margin-bottom: 40px; text-align: left ">
        <h1><span style="color: #e16262;">Employee Concept </span>{{'func_oport'|localize}} </h1>
      </div>
      <div style="margin: 40px; text-align: left; text-size: ">
        <p>{{"FunctionPage0"|localize}}</p>
      </div>

        <b-row align-v="center">
                   <!-- 1 -->
          <b-col class="md-4" style=" text-align: left;  " >
                <h1>{{"FunctionPage1"|localize}}</h1>
                 <img width="270px" src="../imgs/func1.png">

                 <b-card  >
                   <p>Повышаем эффективность HR-процессов<br> за счет внедрения мобильных технологий</p>
                </b-card>
          </b-col>
            <!-- 2 -->
          <b-col  class="md-4" style=" text-align: left;  " >
                <h1>Адаптация</h1>
                 <img width="270px" src="../imgs/func1.png">

                 <b-card>
                 
                  
                   <p>Повышаем эффективность HR-процессов<br> за счет внедрения мобильных технологий</p>
                </b-card>
          </b-col>
          <!-- 3 -->
          <b-col class="md-4" style=" text-align: left;  " >
                <h1>Адаптация</h1>
                 <img width="270px" src="../imgs/func1.png">

                 <b-card >
                 
                  
                   <p>Повышаем эффективность HR-процессов<br> за счет внедрения мобильных технологий</p>
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
