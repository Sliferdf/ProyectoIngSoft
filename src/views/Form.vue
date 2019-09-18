<template>
    <div>
        <h1>Formularios</h1>
        <b-form>
            <b-row>
                <b-col cols="12" md="3">
                        <b-form-input type="text" v-model="texto" :state="comprobar"></b-form-input>
                                <p>Texto:{{texto}}</p>
                </b-col>
              <b-col>
                  <b-form-select v-model="select" :options="animales"></b-form-select>
                  <p>Select:{{select}}</p>
              </b-col>
              <b-col md="3">
                  <b-form-radio-group v-model="radio" :options="animalesRadio">
                      <p>Radio:{{radio}}</p>
                  </b-form-radio-group>
              </b-col>
              <b-col>
                  <b-form-checkbox-group v-model="check" :options="animalesRadio"></b-form-checkbox-group>
                  <p>Check:{{check}}</p>
              </b-col>
            </b-row>
        </b-form>
            </div>
</template>

<script>
export default {
    name:'Form',
    data(){
        return{
            texto:'',
            radio:null,
            check:[],
            select:null,
            animales:[
                {value:null,text:'Seleccione un animal'},
                {value:'Perro',text:'Guau Guau'},
                {value:'Gato',text:'Miau Miau'},
                {value:'Tigre',text:'Jaaa Jaa'}
            ],
            animalesRadio:[
                {value:'Perro',text:'Guau Guau'},
                {value:'Gato',text:'Miau Miau'},
                {value:'Tigre',text:'Jaaa Jaa'}



            ]


        }
    },
    computed: {
        comprobar(){
         return this.texto.length >2 ? true:false
        }
    }, 
}
</script>
