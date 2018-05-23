<template>
    <div>
        <h1>
            Register (ลงทะเบียน)
        </h1>
        <v-text-field v-model="user" label="UserName" />
        <v-text-field v-model="pass" type="password" label="Password" />
        <v-text-field v-model="pass2" type="password" label="Password Again" />
        <v-btn label="Regis" @click="register"><v-icon>track_changes</v-icon>Register</v-btn> 
    </div>
</template>
<script>
export default {
    data(){
        return{
            user:'',
            pass: '',
            pass2: '',
        }
    },
    methods: {
        registor(){
            
        }

    }
}
</script>

