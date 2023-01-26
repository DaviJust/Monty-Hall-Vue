<template>
  <div class="door-area">
    <div class="door-frame">
        <Gift/>
    </div>
    <div class="door">
        <div class="number">{{ number }}</div>
        <div class="knob"></div>
    </div>
  </div>
</template>

<script>
import GiftDoor from './GiftDoor.vue'

export default {
name: 'DoorMonty',
components: {GiftDoor},
props:{
    number:{},
    hasGift: {type: Boolean}
},
data:function(){
    return {
        open: false,
        selected: false
    }
}
}
</script>

<style>

</style>