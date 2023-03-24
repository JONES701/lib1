<template>
    <div class="center">
        <v-row>
            <v-col cols="10" offset="1" xs="6" offset-xs="3" md="4" offset-md="4">
                <h1>Login</h1>
                <v-avatar color="primary" size="110">
                <v-img src="../assets/sample1.jpg"></v-img>
            </v-avatar>
            <v-text-field label="Username" type="username"> Username</v-text-field>
            <v-text-field label="Password" type="password"> Password</v-text-field>
            <v-btn block @click="onclick()"> Submit</v-btn>
            </v-col>
        </v-row>
    </div>
    <!-- <hello-world /> -->
  </template>
  
  <script>
// import { LoaderTargetPlugin } from 'webpack';

  
    export default {
        name: 'login',
        data(){
            return{
                username:"",
                password:""
            }      
        },

        methods:{
            onclick(){
        alert('Login pressed')
      },
  
    }
    }
  </script>