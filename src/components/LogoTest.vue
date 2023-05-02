<template>
    <div class="logotest-wrapper">
        <h1>GetSet,GO！～キヴォトス晄輪大祭～</h1>
        <h2>Card List</h2>
        <div class="item-logos">
            <img class="card" 
            src="../assets/1.png" alt="">
        </div>
        <div class="item-logos">
            <img class="card" 
            src="../assets/2.png" alt="">
        </div>
        <div class="item-logos">
            <img class="card" 
            src="../assets/3.png" alt="">
        </div>
        <div class="item-logos">
            <img class="card" 
            src="../assets/4.png" alt="">
        </div>
        <div class="item-logos">
            <img class="card" 
            src="../assets/5.png" alt="">
        </div>
        <div class="item-logos">
            <img class="card" 
            src="../assets/6.png" alt="">
        </div>
        <div class="item-logos">
            <img class="card" 
            src="../assets/7.png" alt="">
        </div>
        <div class="item-logos">
            <img class="card" 
            src="../assets/8.png" alt="">
        </div>
        <div class="item-logos">
            <img class="card" 
            src="../assets/9.png" alt="">
        </div>
        <div class="item-logos">
            <img class="card" 
            src="../assets/10.png" alt="">
        </div>
    </div>
    <div class="event-image">
        <h2>Event Picture</h2>
        <div class="event-image-list">
            <img class="image-list" 
            src="../assets/23.png" alt="">
        </div>
        <div class="event-image-list">
            <img class="image-list" 
            src="../assets/24.png" alt="">
        </div>
        <div class="event-image-list">
            <img class="image-list" 
            src="../assets/25.png" alt="">
        </div>
        <div class="event-image-list">
            <img class="image-list" 
            src="../assets/26.png" alt="">
        </div>
        <div class="event-image-list">
            <img class="image-list" 
            src="../assets/27.png" alt="">
        </div>
        <div class="event-image-list">
            <img class="image-list" 
            src="../assets/28.png" alt="">
        </div>
    </div>
    <div class="logotest-footer">
        © 2021 NEXON Korea Corp. & NEXON GAMES Co., Ltd. All Rights Reserved.
    </div>
</template>

<script>
export default {
    name: 'LogoTest'
}
</script>

<style scoped>
.logotest-wrapper{
    width: 70%;
    overflow: hidden;
    margin: auto;
}
.item-logos{
    float: left;
    margin-left: 1%;
    margin-right: 1%;
    margin-top: 1%;
    width: 18%;
}
.item-logos .card{
    width: 100%;
    height: auto;
}

.event-image{
    width: 70%;
    overflow: hidden;
    margin: auto;
}

.event-image-list{
    float: left;
    width: 48%;
    margin-left: 1%;
    margin-right: 1%;
    margin-top: 1%;
}

.event-image-list .image-list{
    width: 100%;
    height: auto;
}

.logotest-footer{
    padding-top: 5%;
    width: 70%;
    overflow: hidden;
    margin: auto;
}

</style>