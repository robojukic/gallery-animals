<template>
  <div class=" w-full flex flex-col">
    <header class="w-[1140px] max-w-[80%] m-auto h-[50px] flex items-center z-50 relative">
      <nav>
        <a href="" class="mr-10">Home</a>
        <a href="" class="mr-10">Contacts</a>
        <a href="" class="mr-10">Info</a>
      </nav>
    </header>
    <div class=" carousel w-screen h-screen overflow-hidden -mt-[50px] relative" :class="{ 'next': nextActive }">
      <div class="list">
        <div class="item absolute top-0 left-0 bottom-0 right-0">
          <img src="../../public/image/img1.jpg" class="w-full h-full object-cover" />
          <div
            class="content  absolute top-[20%] w-[1140px] max-w-[80%] left-1/2 transform -translate-x-1/2 box-border pr-[30%] text-[#fff]">
            <div class="author font-bold tracking-[10px]">LUNDEV</div>
            <div class="title font-bold text-[5em] list-[1.3em]">DESIGN SLIDER</div>
            <div class="topic font-bold text-[5em] list-[1.3em] text-[#f1683a]">ANIMAL</div>
            <div class="des">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam convallis arcu dui, at imperdiet
              purus elementum a.</div>
            <div class="buttons flex flex-row gap-2 mt-5">
              <button
                class=" bg-white border-none tracking-[3px] font-bold text-black h-10 w-[130px] flex items-center justify-center ">SEE
                MORE</button>
              <button
                class=" bg-transparent border border-white tracking-[3px] font-bold text-white h-10 w-[130px] flex items-center justify-center ">SUBSCRIBE</button>

            </div>
          </div>
        </div>
        <div class="item absolute top-0 left-0 bottom-0 right-0">
          <img src="../../public/image/img2.jpg" class="w-full h-full object-cover" />
          <div
            class="content absolute top-[20%] w-[1140px] max-w-[80%] left-1/2 transform -translate-x-1/2 box-border pr-[30%] text-[#fff]">
            <div class="author font-bold tracking-[10px]">LUNDEV</div>
            <div class="title font-bold text-[5em] list-[1.3em]">DESIGN SLIDER</div>
            <div class="topic font-bold text-[5em] list-[1.3em] text-[#f1683a]">ANIMAL</div>
            <div class="des">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam convallis arcu dui, at imperdiet
              purus elementum a.</div>
            <div class="buttons flex flex-row gap-2 mt-5">
              <button
                class=" bg-white border-none tracking-[3px] font-bold text-black h-10 w-[130px] flex items-center justify-center ">SEE
                MORE</button>
              <button
                class=" bg-transparent border border-white tracking-[3px] font-bold text-white h-10 w-[130px] flex items-center justify-center ">SUBSCRIBE</button>

            </div>
          </div>
        </div>
        <div class="item absolute top-0 left-0 bottom-0 right-0">
          <img src="../../public/image/img3.jpg" class="w-full h-full object-cover" />
          <div
            class="content  absolute top-[20%] w-[1140px] max-w-[80%] left-1/2 transform -translate-x-1/2 box-border pr-[30%] text-[#fff]">
            <div class="author font-bold tracking-[10px]">LUNDEV</div>
            <div class="title font-bold text-[5em] list-[1.3em]">DESIGN SLIDER</div>
            <div class="topic font-bold text-[5em] list-[1.3em] text-[#f1683a]">ANIMAL</div>
            <div class="des">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam convallis arcu dui, at imperdiet
              purus elementum a.</div>
            <div class="buttons flex flex-row gap-2 mt-5">
              <button
                class=" bg-white border-none tracking-[3px] font-bold text-black h-10 w-[130px] flex items-center justify-center ">SEE
                MORE</button>
              <button
                class=" bg-transparent border border-white tracking-[3px] font-bold text-white h-10 w-[130px] flex items-center justify-center ">SUBSCRIBE</button>

            </div>
          </div>
        </div>
        <div class="item absolute top-0 left-0 bottom-0 right-0">
          <img src="../../public/image/img4.jpg" class="w-full h-full object-cover" />
          <div
            class="content absolute top-[20%] w-[1140px] max-w-[80%] left-1/2 transform -translate-x-1/2 box-border pr-[30%] text-[#fff]">
            <div class="author font-bold tracking-[10px]">LUNDEV</div>
            <div class="title font-bold text-[5em] list-[1.3em]">DESIGN SLIDER</div>
            <div class="topic font-bold text-[5em] list-[1.3em] text-[#f1683a]">ANIMAL</div>
            <div class="des">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam convallis arcu dui, at imperdiet
              purus elementum a.</div>
            <div class="buttons flex flex-row gap-2 mt-5">
              <button
                class=" bg-white border-none tracking-[3px] font-bold text-black h-10 w-[130px] flex items-center justify-center ">SEE
                MORE</button>
              <button
                class=" bg-transparent border border-white tracking-[3px] font-bold text-white h-10 w-[130px] flex items-center justify-center ">SUBSCRIBE</button>

            </div>
          </div>
        </div>
      </div>
      <!--Thumbnail-->
      <div class="thumbnail absolute bottom-[50px] left-1/2 w-max z-50 flex gap-5">
        <div class="item w-[150px] h-[220px] shrink-0 relative">
          <img src="../../public/image/img1.jpg" class="w-full h-full object-cover rounded-[20px]" />
          <div class="absolute bottom-[10px] left-[10px] right-[10px]">
            <div class=" font-bold">Name Slider</div>
            <div class="des">Description</div>
          </div>
        </div>
        <div class="item w-[150px] h-[220px] shrink-0 relative">
          <img src="../../public/image/img2.jpg" class="w-full h-full object-cover rounded-[20px]" />
          <div class="absolute bottom-[10px] left-[10px] right-[10px]">
            <div class=" font-bold">Name Slider</div>
            <div class="des">Description</div>
          </div>
        </div>
        <div class="item w-[150px] h-[220px] shrink-0 relative">
          <img src="../../public/image/img3.jpg" class="w-full h-full object-cover rounded-[20px]" />
          <div class="absolute bottom-[10px] left-[10px] right-[10px]">
            <div class=" font-bold">Name Slider</div>
            <div class="des">Description</div>
          </div>
        </div>
        <div class="item w-[150px] h-[220px] shrink-0 relative">
          <img src="../../public/image/img4.jpg" class="w-full h-full object-cover rounded-[20px]" />
          <div class="absolute bottom-[10px] left-[10px] right-[10px]">
            <div class=" font-bold">Name Slider</div>
            <div class="des">Description</div>
          </div>
        </div>
      </div>
      <!--Arrows-->
      <div class="absolute z-50 top-[80%] right-[52%] w-[300px] max-w-[30%] flex gap-4">
        <button
          class="w-10 h-10 rounded-[50%] bg-[#eee4] border-none font-mono text-white font-bold hover:bg-[#eee] hover:text-[#555] transition-all duration-500">&#60;</button>
        <button @click="nextFunction()"
          class="w-10 h-10 rounded-[50%] bg-[#eee4] border-none font-mono text-white font-bold hover:bg-[#eee] hover:text-[#555] transition-all duration-500">&#62;</button>
      </div>
      <div class="time"></div>
    </div>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue';
const nextActive = ref(false)

const nextFunction = () => {
  nextActive.value = true;
  // Add a timeout of 2 seconds (2000 milliseconds)
  setTimeout(() => {
    nextActive.value = false;
  }, 2000);
}
</script>

<style>
.carousel .list .item:nth-child(1) {
  z-index: 1;
}

.carousel .list .item:nth-child(1) .author,
.carousel .list .item:nth-child(1) .title,
.carousel .list .item:nth-child(1) .topic,
.carousel .list .item:nth-child(1) .des,
.carousel .list .item:nth-child(1) .buttons {
  transform: translateY(50px);
  filter: blur(20px);
  opacity: 0;
  animation: showContent 0.5s 1s linear 1 forwards;
}

@keyframes showContent {
  to {
    opacity: 1;
    filter: blur(0);
    transform: translateY(0);
  }
}

.carousel .list .item:nth-child(1) .title {
  animation-delay: 1.2s;
}

.carousel .list .item:nth-child(1) .topic {
  animation-delay: 1.4s;
}

.carousel .list .item:nth-child(1) .des {
  animation-delay: 1.6s;
}

.carousel .list .item:nth-child(1) .buttons {
  animation-delay: 1.8s;
}

.carousel.next .list .item:nth-child(1) img {
  width: 150px;
  height: 220px;
  position: absolute;
  left: 50%;
  bottom: 50px;
  border-radius: 20px;
  animation: showImage 0.5s linear 1 forwards;
}

@keyframes showImage {
  to {
    width: 100%;
    height: 100%;
    left: 0;
    bottom: 0;
    border-radius: 0;
  }
}

.carousel.next .thumbnail .item:nth-last-child(1) {
  width: 0;
  overflow: hidden;
  animation: showThumbnail 0.5s linear 1 forwards;
}

@keyframes showThumbnail {
  to {
    width: 150px;
  }
}

.carousel.next .thumbnail {
  transform: translateX(150px);
  animation: transformThumbnail 0.5s linear 1 forwards;
}

@keyframes transfromThumbnail {
  to {
    transform: translateX(0)
  }
}

.carousel.prev .list .item:nth-child(2) {
  z-index: 2;
}

.carousel.prev .list .item:nth-child(2) img {
  position: absolute;
  bottom: 0;
  left: 0;
  animation: outImage 0.5s linear 1 forwards;
}

@keyframes outImage {
  to {
    width: 150px;
    height: 220px;
    border-radius: 20px;
    left: 50%;
    bottom: 50px;
  }
}

.carousel.prev .list .item:nth-child(1) {
  width: 0;
  overflow: hidden;
  opacity: 0;
  animation: showThumbnail 0.5s linear 1 forwards;
}

.carousel.prev .list .item:nth-child(2) .author,
.carousel.prev .list .item:nth-child(2) .title,
.carousel.prev .list .item:nth-child(2) .topic,
.carousel.prev .list .item:nth-child(2) .des,
.carousel.prev .list .item:nth-child(2) .buttons {
  animation: contentOut 1.5s linear 1 forwards;
}

@keyframes contentOut {
  to {
    transform: translateY(150px);
    filter: blur(20px);
    opacity: 0;
  }
}

.carousel.next .arrows button,
.carousel.prev .arrows button {
  pointer-events: none;
}

.time {
  width: 0%;
  height: 3px;
  background-color: #f1683a;
  position: absolute;
  z-index: 100;
  top: 0;
  left: 0;
}

.carousel.next .time,
.carousel.prev .time {
  width: 100%;
  animation: timeRunning 2s linear 1 forwards;
}

@keyframes timeRunning {
  to {
    width: 0
  }
}

@media screen and (max-width:678px) {
  .carousel .list .item .content {
    padding-right: 0;
  }

  .carousel .list .item .content .title {
    font-size: 30px;
  }
}
</style>