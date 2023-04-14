<template>
    <section>

        <h2>logo</h2>

        <nav>
            <p> Link 1 </p>
            <p> Link 2 </p>
            <p> Link 3 </p>
            <p> Link 4 </p>
        </nav>
    </section>
</template>

<script>
    export default {
        
    }
</script>

<style>
section{
    display: grid;
    grid-template-columns: 1fr 1fr;
    align-items: center;
    background-color: gainsboro;
    max-height: 10vh;
}
nav{
    margin: 0px;
    padding: 0px;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;

}
    
</style>