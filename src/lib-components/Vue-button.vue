<template>
    <button :type="type" :class="classname">{{text}}</button>
</template>
<script>

export default {
    name: 'UIbutton',
    props: {
        text: String,
        active: String,
        type: String,
        classname:String,
    },
};
</script>

<style>
.outlined {
    background: transparent;
    border: 2px solid #475447;
    width: 140px;
    height: 42px;
    margin: 6%;
}
.background {
    background-color:#73E8A3;
    border-radius: 50px;
    width: 140px;
    height: 42px;
    margin: 6%;
}
</style>