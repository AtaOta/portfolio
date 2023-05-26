<script setup>
</script>

<template>
    <div class="ProfileWrapper">
        <div class="ProfilePicture">
            2K
        </div>
    </div>
</template>

<style scoped>
.ProfileWrapper {
    position: relative;
    width: 200px;
    height: 200px;
    border: 2px solid red;
    border-right: 2px solid transparent;
    border-bottom: 2px solid #ae00ffad;
    border-left: 2px solid transparent;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    /* -webkit-animation: spin 8s linear infinite;
    animation: spinProfileWrapper 8s linear infinite; */
}

/* @-webkit-keyframes spinProfileWrapper {
  0% { -webkit-transform: rotate(0deg); }
  100% { -webkit-transform: rotate(360deg); }
}

@keyframes spinProfileWrapper {
  0% { transform: rotate(0deg); }
  100% { transform: rotate(360deg); }
} */
.ProfileWrapper::before {
    content: "";
    position: absolute;
    background-color: transparent;
    width: 400px;
    height: 400px;
    border-radius: 50%;
    border: 150px solid black;
    border-top: 150px solid transparent;
    border-right: 150px solid transparent;
    border-bottom: 150px solid transparent;
    -webkit-animation: spin 5s linear infinite;
    animation: spinProfileWrapperBefore 5s linear infinite;
}

@-webkit-keyframes spinProfileWrapperBefore {
    0% {
        -webkit-transform: rotate(0deg);
    }

    100% {
        -webkit-transform: rotate(-360deg);
    }
}

@keyframes spinProfileWrapperBefore {
    0% {
        transform: rotate(0deg);
        border: 100px solid #ff000093;
        border-top: 100px solid transparent;
        border-right: 100px solid transparent;
        border-bottom: 100px solid transparent;
    }
    45%{
        width: 200px;
        height: 200px;
        border: 0px solid #ffa2a2;
        border-top: 0px solid transparent;
        border-right: 0px solid transparent;
        border-bottom: 0px solid transparent;
    }
    55%{
        width: 200px;
        height: 200px;
        border: 0px solid #ff000083;
        border-top: 0px solid transparent;
        border-right: 0px solid transparent;
        border-bottom: 0px solid transparent;
    }

    100% {
        transform: rotate(-360deg);
        border: 100px solid #44f9ff;
        border-top: 100px solid transparent;
        border-right: 100px solid transparent;
        border-bottom: 100px solid transparent;
    }
}

.ProfileWrapper::after {
    content: "";
    position: absolute;
    background-color: transparent;
    width: 200px;
    height: 200px;
    border-radius: 50%;
    border: 50px solid #019119;
    border-left: 50px solid transparent;
    border-top: 50px solid transparent;
    border-bottom: 50px solid transparent;
    -webkit-animation: spin 5s linear infinite;
    animation: spinProfileWrapperAfter 5s linear infinite;
}

@-webkit-keyframes spinProfileWrapperAfter {
    0% {
        -webkit-transform: rotate(0deg);
    }

    100% {
        -webkit-transform: rotate(360deg);
    }
}

@keyframes spinProfileWrapperAfter {
    0% {
        transform: rotate(0deg);
    }
    30%{
        width: 200px;
        height: 200px;
        border: 50px solid #00ff95;
        border-left: 50px solid transparent;
        border-top: 50px solid transparent;
        border-bottom: 50px solid transparent;
    }
    45%{
        width: 100px;
        height: 100px;
        border: 0px solid #00ffbf9f;
        border-left: 0px solid transparent;
        border-top: 0px solid transparent;
        border-bottom: 0px solid transparent;
    }
    55%{
        width: 100px;
        height: 100px;
        border: 0px solid #00ebb8;
        border-left: 0px solid transparent;
        border-top: 0px solid transparent;
        border-bottom: 0px solid transparent;
    }

    100% {
        transform: rotate(360deg);
    }
}

.ProfilePicture {
    height: 100px;
    width: 100px;
    border: 2px solid #00eeff;
    border-right: 2px solid transparent;
    border-left: 2px solid transparent;
    box-sizing: border-box;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 50px;
    font-weight: bold;
    text-shadow: 0px 0px 5px #000000;
    color: #fff;
}
.ProfilePicture::before {
    content: "";
    position: absolute;
    background-color: transparent;
    width: 300px;
    height: 300px;
    border-radius: 50%;
    border: 100px solid red;
    border-top: 100px solid transparent;
    border-right: 100px solid transparent;
    border-bottom: 100px solid transparent;
    /* box-shadow: 0px 0px 5px #00eeff; */
    -webkit-animation: spin 5s linear infinite;
    animation: spinProfilePictureBefore 5s linear infinite;
}
@keyframes spinProfilePictureBefore {
    30%{
        border: 100px solid red;
        border-top: 100px solid transparent;
        border-right: 100px solid transparent;
        border-bottom: 100px solid transparent;
    }
    45%{
        border: 0px solid #00d9ff;
        border-left: 0px solid transparent;
        border-top: 0px solid transparent;
        border-bottom: 0px solid transparent;
    }
    55%{
        border: 0px solid #00d9ff;
        border-left: 0px solid transparent;
        border-top: 0px solid transparent;
        border-bottom: 0px solid transparent;
    }
    100%{
        border: 100px solid #00d9ff;
        border-top: 100px solid transparent;
        border-right: 100px solid transparent;
        border-bottom: 100px solid transparent;
    }
}
.ProfilePicture::after {
    content: "";
    position: absolute;
    background-color: transparent;
    width: 250px;
    height: 250px;
    border-radius: 50%;
    border: 50px solid #ae00ffad;
    border-left: 50px solid transparent;
    border-top: 50px solid transparent;
    border-bottom: 50px solid transparent;
    box-shadow: 0px 0px 5px #888888;
    -webkit-animation: spin 5s linear infinite;
    animation: spinProfilePictureAfter 5s linear infinite;
}
@keyframes spinProfilePictureAfter {
    30%{
        border: 50px solid #e100ffb6;
        border-left: 50px solid transparent;
        border-top: 50px solid transparent;
        border-bottom: 50px solid transparent;
    }
    45%{
        border: 0px solid #e100ff93;
        border-left: 0px solid transparent;
        border-top: 0px solid transparent;
        border-bottom: 0px solid transparent;
    }
    55%{
        border: 0px solid #e100ff71;
        border-left: 0px solid transparent;
        border-top: 0px solid transparent;
        border-bottom: 0px solid transparent;
    }
}
</style>
