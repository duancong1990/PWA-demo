<template>
    <div>
        <div class='title'>欢迎试用PWA网页</div>
        <div class='img'>
            <!-- <img src='https://lorempixel.com/400/200/' ref='img'> -->
            <img src='./img/pic1.jpg' >
            <!-- <img src='./img/pic2.jpg' >
            <img src='./img/pic3.jpg' >
            <img src='./img/pic4.jpg' >
            <img src='./img/pic5.jpg' >
            <img src='./img/pic6.jpg' >
            <img src='./img/pic7.jpg' >
            <img src='./img/pic8.png' >
            <img src='./img/pic9.jpg' >
            <img src='./img/pic10.jpg' > -->
        </div>
        <div>
            <button>订阅图片</button>
        </div>
        <div class='message'>
            <p>
                you can subscribe, then we will message you picture change. dont you want see new picture?
                its beatiful.
            </p>
        </div>
    </div>
</template>

<script>
export default {
    name: 'index',
    mounted () {
        // let img = this.$refs.img;
        // this.fresh(img);
    },
    methods: {
        fresh (img) {
            // var imgFresh = setInterval(function () {
            //     let testimg = document.createElement('img');
            //     testimg.src = 'https://lorempixel.com/400/200/';
            //     // 如果有网的话在刷新
            //     testimg.onload = () => {
            //         img.src = 'https://lorempixel.com/400/200/';
            //     }
            //     testimg.onerror = () => {
            //         clearInterval(imgFresh);
            //         setTimeout(this.fresh, 180000);
            //     };
            // }, 30000);
        }
    }
}
</script>
<style lang='less'>
div {
    text-align: center;
}
.title {
    margin-top: 10px;
    font-weight: bold;
}
.img {
    margin-top: 100px;
    box-sizing: border-box;
}
img {
    height: 45%;
    width: 90%;
    max-width: 400px;
    max-height: 200px;
}
button {
    margin-top: 10px;
    width: 150px;
    height: 40px;
    background: #9cc2f4;
    border: none;
    box-shadow: 2px 4px 10px 0px #d1e3fa;
    outline: none;
}
button:active {
    box-shadow: 2px 4px 10px 0px #d1f3fa;
}
.message {
    margin-top: 30px;
    text-align: center;
    padding: 0px 10%;
    p {
        margin: 0 auto;
        display: inline;
        text-align: justify; 
    }
}
</style>

