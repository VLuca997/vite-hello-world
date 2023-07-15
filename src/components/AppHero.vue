<script>
import gokuImage from '../assets/goku.jpg'; // importo la foto di golu e poi la rendo una variabile da applicare a :src="gokuImage"
export default {
    data() {
        return { 
            gokuImage: gokuImage
        }
    },
}
</script>
<template>
    <div class="jumbotron">
        <div class="imgContain">
            <img :src="gokuImage" alt="GOKU">

        </div>
    </div>
</template>
<style scoped>

    .jumbotron > .imgContain{
        display: flex;
        justify-content: center;
    }
    img{
        max-width: 100%;
        background-size: cover;
    }
    .imgContain{
        height: 500px;
        width: 500px;
        border: 3px dashed white;

    }
</style>