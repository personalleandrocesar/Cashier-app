<script setup>


</script>
<template>
        <Cashier />
        <NuxtPage />
</template>
<style scoped>
.link {
   display: flex;
   justify-content: space-evenly;
   margin-top: 1.5rem;
   font-size: 1.2rem;
   font-weight: bolder;
   backdrop-filter: blur(5px);
}

a {
    border-bottom: solid 2px #71809690;
    letter-spacing: 2px;
    width: 40%;
    text-align: center;
    cursor: pointer;
}

a:hover {
    border-bottom: solid 2px #34d399;
    color: #34d399;
    cursor: pointer;
}

a.router-link-exact-active {
    border-bottom: solid 2px #34d399;
    color: #34d399;
}

.aActivee {
    border-bottom: solid 2px #34d399;
    color: #34d399;
    
}

</style>
