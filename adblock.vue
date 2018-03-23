<template>
<div>
<div id="wrapfabtest">
    <div class="adBanner">
    </div>
</div>
</div>
</template>

<script>
export default {
    data: function() {
        return {
        }
    },
    mounted: function(){

        var wrap = document.getElementById("wrapfabtest").offsetHeight;
        console.log(wrap)
        if(wrap > 0) {
        alert('No AdBlock :)');
        
         } else {
        alert('AdBlock Detected ');
        
        }
    }
}
</script>

<style scoped>
.adBanner {
    background-color: transparent;
    height: 1px;
    width: 1px;
}
</style>
