---
layout: page
title:
permalink: /blog
---

<h1 align="center">Lab gallery</h1>

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>图片浮动显示</title>
<style>
    .image-container {
        width: 1200px;
        height: 800px;
        position: relative;
        overflow: hidden;
        margin: 0 auto;
    }
    .image-container img {
        width: 100%;
        height: auto;
        position: absolute;
        transition: opacity 0.5s ease-in-out;
    }
</style>
</head>
<body>
<div class="image-container">
    <img src="{{site.baseurl}}/assets/img/gallery/cls.jpg" alt="Image 1">
    <img src="{{site.baseurl}}/assets/img/gallery/grass.jpg" alt="Image 2">
    <img src="{{site.baseurl}}/assets/img/gallery/clean.JPG" alt="Image 3">
    <img src="{{site.baseurl}}/assets/img/gallery/bbq.JPG" alt="Image 4">
</div>

<script>
    document.addEventListener("DOMContentLoaded", function() {
        let images = document.querySelectorAll('.image-container img');
        let currentIndex = 0;
        let interval = 3000; // 每隔3秒切换一次

        function showImage(index) {
            for (let i = 0; i < images.length; i++) {
                if (i === index) {
                    images[i].style.opacity = 1;
                } else {
                    images[i].style.opacity = 0;
                }
            }
        }

        function nextImage() {
            currentIndex = (currentIndex + 1) % images.length;
            showImage(currentIndex);
        }

        setInterval(nextImage, interval);
        showImage(currentIndex);
    });
</script>
</body>
</html>

