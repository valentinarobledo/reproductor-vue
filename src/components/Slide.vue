<template>
    <div class="app">
        <div class="user_img">
            <img  class="avatar" width="100" src="../assets/avatar.jpg" alt="">
        </div>
        <div class="user_name">Valentina Robledo</div>
        <div class="user_email">valenrobledo31@gmail.com</div>

        <div class="menu">
            <li>Home</li>
            <li> <i class="fas fa-home"></i>Browser</li>
            <li>Album</li>
            <li>Artist</li>
            <li>Videos</li>
        </div>
        <div class="section">MY MUSIC</div>
        <div class="menu">
            <li>Recently Played</li>
            <li>Local Files</li>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>
<style lang="scss">
.user_img{
    margin-bottom:1em;
}
.avatar{
    border-radius:50px;
    box-shadow:2px 2px 6px 0px rgba(37, 34, 34, 0.2);
}
.user_name{
    font-size:20px;
    font-weight: 700;
    margin-bottom:0.5em;
    color:#4b4b4b;
}
.user_email{
    color:#afafaf;
}
.menu{
    margin-top:2em;
    list-style: none;
    text-align: left;
    padding-left:12em;
    font-weight: 600;
}
li{
    margin-bottom:1em;
}
.section{
    text-align: center;
    margin-top:2em;
    color:#afafaf;
    letter-spacing: 0.2em;
}
</style>