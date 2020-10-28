<template>
    <div class="search">
        <input type="text" placeholder="Search for song, artist, etc">
        <div class="upgrade">Upgrade</div>
    </div>
</template>
<style lang="scss">
.search{
    display:flex;
}
input{
    width:500px;
    height:30px;
    border-radius:30px;
    text-align: center;
}
.upgrade{
    margin-left:10em;
    background: #f12711;  /* fallback for old browsers */
    background: -webkit-linear-gradient(to right, #f5af19, #f12711);  /* Chrome 10-25, Safari 5.1-6 */
    background: linear-gradient(to right, #f5af19, #f12711); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
    width:150px;
    height:30px;
    color:white;
    font-weight: 800;
    text-align: center;
    padding-top:0.6em;
    border-radius:30px;
    cursor:pointer;
    &:hover{
        margin-top:0.2em;
        background:black;
    }
}
</style>