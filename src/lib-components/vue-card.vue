<template>
    <div :class="alignment">
        <h2>Alert Heading</h2>
        <p>Alert description Lorem Ipsum</p>
        <Buttoncomponent classname="background" text="Click Me"/>
        <Buttoncomponent classname="outlined" text="Click Me"/>
    </div>
</template>
<script>
import Buttoncomponent from './Vue-button.vue';

export default {
    name:'UIcard',
    components: {
        Buttoncomponent,
    },
        props: {
            alignment: String,
        },
};
</script>

<style>
.horizontal {
    height: 100%;
    width: 30%;
    padding: 4%; 
    border: 2px solid black;
}

.horizontal h2 {
    font-size: 164%;
} 

.vertical {
    height: 80%;
    width: 26%;
    padding: 2%; 
    border: 2px solid black;
}

.vertical h2 {
    font-size: 164%;
}
</style>