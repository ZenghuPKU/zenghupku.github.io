---
layout: page
permalink: /home1
---

<style>
  table {
    width: 100%;
  }
  .img-cell {
    width: 25%; /* 分配25%宽度给图片 */
  }
  .img-cell img {
    width: 100%; /* 图片宽度自适应单元格 */
    height: auto;
  }
  .text-cell {
    width: 25%; /* 分配25%宽度给文字 */
  }


  .imgContainer{
         display: flex;
    width: 100%;
    flex-wrap: wrap;
    justify-content: space-between;
    }
   
    .imgContainer li{
      list-style: none;
    margin: 20px 0;
width: 49%;
    display: flex;
    }
    .imgContainer .imgWrap{
    display: flex;
    justify-content: center;
    align=-items: center;
          width: 50%;

    padding: 20px;
    }
    .imgContainer li .content{
      width: 50%;
      padding: 0px 20px;
    }
    .text .content{
      width: 100% !important;

    }
    .imgContainer li .content p {
      line-height: 30px;
    }
    .imgContainer li img{
      width: 300px;
        height: fit-content;
    }
    .imgContainer h4{
      margin: 0;
      line-height: 50px;
    }
    .btn{
          color: #fff;
              text-decoration: none;
    background-color: #1677ff;
    padding: 5px 20px;
    border-radius:5px;
    display: inline-block;
    box-shadow: 0 2px 0 rgba(5, 145, 255, 0.1);
    }
    a:hover{
      color: #fff;
    }

    .btn_underLine{
      text-decoration: underline;
      background: none;
    box-shadow: none;

      color: #1677ff;
    }
    .btn_underLine:hover{
           color: #1677ff;

    }
    h5{
      font-size: 30px;
      font-weight: 200;
      margin: 15px 0;
    }
</style>

<ul class="imgContainer">

    <li style="width: 100%">
      <div class="imgWrap">
          <img src="https://zenghulab.github.io/picx-images-hosting/image/research.231pjlwm8o.webp" alt="research" />

      </div>
      <div class="content">
        <h4>Welcome to the Zeng Lab</h4>
      <p class="text-muted" style="font-size:90%;line-height: 1em;">Postdoctoral Fellow</p>
      <p style="font-size:90%">The flow of genetic information in cells is from DNA through RNA to protein, which is a fundamental principle and termed the central dogma of molecular biology. Our research program focuses on the central dogma to develop sequencing technologies with spatial, temporal, and single-cell resolution. We apply these sequencing technologies to decipher gene regulatory networks and discover neurological disease mechanism in spatial and temporal dimensions. </p>
      <a class="btn" href="/research.html">Research</a>
      </div>
  </li>

  <li class="text">
     
      <div class="content">
        <h5>Recent News</h5>
 <p>SIMPLE-seq is out at Nature Biotechnology! SIMPLE-seq is a multi-omics sequencing technology that simultaneously measures 5mC and 5hmC at the single-cell and single-molecule levels.</p>
      <a class="btn btn_underLine" href="/news.html">News</a>
      </div>
  </li>

  <li class="text">

      <div class="content">
        <h5>Join us!</h5>
      <p>We are looking for talented scientists at all levels! If you are excited about developing single-cell epigenomics technologies, making discoveries about gene regulation in development and diseases, please do not hesitate to contact us. </p>
      <a class="btn btn_underLine" href="/contact.html">Contact</a>
      </div>
  </li>
</ul>