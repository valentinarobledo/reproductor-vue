<template>
    <div class="music">
        <div class="songs">
            <h3>Songs</h3>
            <div class="song" v-for="(item, index) in music" :key="index">
                <div class="index">{{index+1}}</div>
                <img class="img-song"  width="50" src="../assets/img/img1.jpg" alt="">
                <li class="name-song">{{item.name}}</li>
                <li class="duration-song">{{item.duration}}</li>
             </div>
        </div>
    </div>
</template>
<script>

export default {
    data(){
        return{
            music:[
            {
                "id":"1",
                "name":"Find the key",
                "duration":"3:22",
                "img":"../assets/img/img1.jpg",
                "audio":"../assets/audio/audio1.mp3"
            },
            {
                "id":"2",
                "name":"Good News",
                "duration":"4:30",
                "img":"../assets/img/img2.jpg",
                "audio":"../assets/audio/audio2.mp3"
            },
            {
                "id":"3",
                "name":"Ligth of hope",
                "duration":"3:10",
                "img":"../assets/img/img3.jpg",
                "audio":"../assets/audio/audio3.mp3"
            },
            {
                "id":"4",
                "name":"Season of joy",
                "duration":"2:57",
                "img":"../assets/img/img4.jpg",
                "audio":"../assets/audio/audio4.mp3"
            },
            {
                "id":"5",
                "name":"Skater",
                "duration":"5:20",
                "img":"../assets/img/img5.jpg",
                "audio":"../assets/audio/audio5.mp3"
            },
            {
                "id":"6",
                "name":"Spring flower",
                "duration":"3:45",
                "img":"../assets/img/img6.jpg",
                "audio":"../assets/audio/audio6.mp3"
            },
            {
                "id":"7",
                "name":"The first light",
                "duration":"4:18",
                "img":"../assets/img/img7.jpg",
                "audio":"../assets/audio/audio7.mp3"
            },
            {
                "id":"8",
                "name":"The quiet solitude",
                "duration":"4:08",
                "img":"../assets/img/img8.jpg",
                "audio":"../assets/audio/audio8.mp3"
            },
            {
                "id":"9",
                "name":"Travel dreams",
                "duration":"2:15",
                "img":"../assets/img/img9.jpg",
                "audio":"../assets/audio/audio9.mp3"
            },
            {
                "id":"10",
                "name":"Winter lover",
                "duration":"6:07",
                "img":"../assets/img/img10.jpg",
                "audio":"../assets/audio/audio10.mp3"
            }
        ]
        }
    },
    
}
</script>
<style lang="scss">

li{
    list-style:none;
}
.song{
    display: flex;
    margin-bottom:2em;
    background:white;
    border-color:#afafaf;
    border-radius:10px;
    cursor:pointer;
}
.index, .img-song, .name-song, .duration-song{
    margin-left:3em;
}
.index, .name-song{
    color:#4b4b4b;
    font-weight: 700;
}
.img-song{
    border-radius:10px;
}
.duration-song{
    color:#afafaf;
    align-items:flex-end;
}
</style>
