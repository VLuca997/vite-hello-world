<script>
export default {
    data() {
        return { 
            message: 'La mia prima app con Vite!'
        }
    },
}
</script>


<template>

    <div>
        <header>
            <h1>
                {{ message }}
            </h1>
        </header>

    </div>

</template>


<style scoped>
    header{
        color: darkblue;
        background-color: yellow;
        border-radius: 25px;
        padding: 1.25rem;
    }   
    h1:hover{
        transform: scale(1.5);
        
        color: white;
        
        
    }
    header:hover{
        transform: scale(1.3);
    }
</style>