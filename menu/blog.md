---
layout: page
title:
permalink: /blog
---

<h1 align="center">Lab Gallery</h1>

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>图片选择显示</title>
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
        opacity: 0;
    }
    .image-container img.active {
        opacity: 1;
    }
    .thumbnail-container {
        display: flex;
        justify-content: center;
        margin-top: 20px;
    }
    .thumbnail-container img {
        width: 150px; /* 缩略图宽度 */
        height: 100px; /* 缩略图高度，保持比例一致 */
        margin: 0 10px;
        cursor: pointer;
        border: 2px solid transparent;
        transition: border 0.3s ease;
        object-fit: contain; /* 保证内容完整显示 */
        background: #f0f0f0; /* 添加背景色以区分透明区域 */
    }
    .thumbnail-container img:hover {
        border: 2px solid #007BFF;
    }
    .thumbnail-container img.selected {
        border: 2px solid #FF0000;
    }
</style>
</head>
<body>
<div class="image-container">
    <img src="{{site.baseurl}}/assets/img/gallery/cls.jpg" alt="Image 1" class="active">
    <img src="{{site.baseurl}}/assets/img/gallery/grass.jpg" alt="Image 2">
    <img src="{{site.baseurl}}/assets/img/gallery/clean.JPG" alt="Image 3">
    <img src="{{site.baseurl}}/assets/img/gallery/island.jpg" alt="Image 4">
</div>

<div class="thumbnail-container">
    <img src="{{site.baseurl}}/assets/img/gallery/cls.jpg" alt="Thumbnail 1" data-index="0" class="selected">
    <img src="{{site.baseurl}}/assets/img/gallery/grass.jpg" alt="Thumbnail 2" data-index="1">
    <img src="{{site.baseurl}}/assets/img/gallery/clean.JPG" alt="Thumbnail 3" data-index="2">
    <img src="{{site.baseurl}}/assets/img/gallery/island.jpg" alt="Thumbnail 4" data-index="3">
</div>

<script>
    document.addEventListener("DOMContentLoaded", function() {
        let images = document.querySelectorAll('.image-container img');
        let thumbnails = document.querySelectorAll('.thumbnail-container img');
        let currentIndex = 0;

        function showImage(index) {
            images.forEach((img, i) => {
                img.classList.toggle('active', i === index);
            });
            thumbnails.forEach((thumb, i) => {
                thumb.classList.toggle('selected', i === index);
            });
        }

        thumbnails.forEach(thumb => {
            thumb.addEventListener('click', function() {
                let index = parseInt(this.getAttribute('data-index'));
                currentIndex = index;
                showImage(currentIndex);
            });
        });

        // Optional: Auto slideshow
        // let interval = 3000; // 每隔3秒切换一次
        // setInterval(() => {
        //     currentIndex = (currentIndex + 1) % images.length;
        //     showImage(currentIndex);
        // }, interval);
    });
</script>
</body>
</html>
