<template>
    <header>
        <h2>Atenea Ecomerce</h2>
        <ul>
            <li> <a href="#">Home</a></li>
            <li> <a href="#">Deals</a></li>
            <li> <a href="#">Chart</a></li>
        </ul>

    </header>


</template>

<script>
    export default {
        name: "HeaderComponent",
    }

</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

header {
    padding: 10px 49px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: rgb(9,9,121);
    background: linear-gradient(90deg, rgba(9,9,121,1) 33%, rgba(2,0,36,1) 71%, rgba(43,0,255,1) 100%);

}

header h2 {
    color: #fff;
    margin: 0;
    padding: 0;
    font-family: "Monserrat", sans-serif;
    font-weight: 400;
}

header ul {
    list-style-type: none;
    display: flex;
    gap: 20px;
}

header a{
    font-family: "Monserrat", sans-serif;
    color: #fff;
    text-decoration: none;
}

</style>

