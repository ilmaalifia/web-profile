<template>
    <div class="profile">
        <b-container class="bv-example-row">
        <b-row>
            <b-col cols=3 align-self="center">
                <div class="image-cropper">
                    <img alt="Profile Picture" src="https://storage.googleapis.com/start-project-274905-bucket/profpic.jpg">
                </div>
            </b-col>
            <b-col align-self="center" class="text-right">
                <div class="vl"></div>
            </b-col>
            <b-col align-self="start" class="text-left">
                <h3><b>Name</b></h3>
                <h3><b>Phone</b></h3>
                <h3><b>Email</b></h3>
                <h3><b>Desc</b></h3>
            </b-col>
            <b-col align-self="start">
                <h3><b>:</b></h3>
                <h3><b>:</b></h3>
                <h3><b>:</b></h3>
                <h3><b>:</b></h3>
            </b-col>
            <b-col cols="6" align-self="start" class="text-justify">
                <h3>Ilma Alifia Mahardika</h3>
                <h3>+62812-XXX-XXX-XX</h3>
                <h3>ilma.mahardika@gmail.com</h3>
                <h3>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse feugiat arcu eu laoreet fringilla.
                    Morbi commodo tincidunt nisi ut porttitor. Morbi congue eget augue ut maximus.
                    Ut pharetra imperdiet tempor. Duis scelerisque pellentesque dictum.
                    Cras a ex eu sapien suscipit vehicula. Praesent pretium ut mauris posuere porttitor.
                    Maecenas varius, sapien et rutrum sagittis, erat nibh vehicula orci, eget commodo ligula nisi eu velit.
                    Cras a ex eu sapien suscipit vehicula. Praesent pretium ut mauris posuere porttitor.
                </h3>
            </b-col>
        </b-row>
        <b-row>
            <b-col cols="8"></b-col>
            <b-col cols="4" class="text-right">
                <a href="https://www.instagram.com/ilmaalifia/" target="_blank"><img src="../assets/instagram.webp" style="width: 70px; padding: 10px"></a>
                <a href="https://ilmaam.blogspot.com/" target="_blank"><img src="../assets/blogger.webp" style="width: 70px; padding: 10px"></a>
            </b-col>
        </b-row>
        </b-container>
    </div>
</template>

<script>
export default {
  name: 'Profile'
}
</script>

<style scoped>
.vl {
  border-left: 6px solid rgb(25, 25, 97);
  height: 500px;
}
.image-cropper {
    width: 225px;
    height: 225px;
    overflow: hidden;
    border-radius: 50%;
}
img {
    width: 225px;
}

h3 {
    font: 1.5em sans-serif;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}
</style>
