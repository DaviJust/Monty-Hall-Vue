<template>
  <div id="app">
    <h1>Problema de Monty Hall</h1>
    <DoorMonty/>
</div>
</template>

<script>
import DoorMonty from './components/DoorMonty'
export default {
name: 'App',
components:{DoorMonty},

}
</script>

<style>
*{
   
    box-sizing: border-box;
    font-family: 'Montserrat', sans-serif;
}
body{
    background: linear-gradient(to right, #1a2980, #26d0ce); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
    color:white;
}
#app{
    display:flex;
    flex-direction: column;
    align-items: center;
}
#app h1{
    border: 1px solid black;
    background-color: #0004;
    padding: 20px;
    margin-bottom:60px;
}
</style>