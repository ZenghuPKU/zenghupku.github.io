---
layout: page
title: 
permalink: /team
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
    padding: 20px;
    flex-wrap: wrap;
    justify-content: space-between;
    }
    .imgContainer li:hover{
    box-shadow: 0px 0px 5px 0px #999;
    transition: .5s;
    }
    .imgContainer li{
      list-style: none;
    margin: 20px 0;
    box-shadow: 0px 0px 2px 0px #999;

    display: flex;
    width: 48%;
    }
    .imgContainer .imgWrap{
          width: 250px;
    display: flex;
    padding: 20px;
    }
    .imgContainer li .content{
      flex: 1;
      padding: 0px 20px;
    }
    .imgContainer li .content p {
      line-height: 30px;
    }
    .imgContainer li img{
      width: 100%;
        height: fit-content;
    }
    .imgContainer h4{
      margin: 0;
      line-height: 50px;
    }
</style>




<h2 align="center">Group Leader</h2>
<table >
<tr> 
<td >
<img src=" {{site.baseurl}}/assets/img/team/zenghu.jpg"  width="800px"/> 
</td> 
<td>
<h4>Hu Zeng (曾虎)</h4>
<p class="text-muted" style="font-size:90%;line-height: 1em;">Assistant Professor for life science at Peking University</p>
                <p style="font-size:90%">Email: huzeng &lt;at&gt; pku.edu.cn<br>Tel: +86 (010) 62767687 <br>
                  <a href="https://future.pku.edu.cn/jsdw/jy/fzyxs1/11e271c0c09e4b919554a49d90093b98.htm" target="_blank">Departmental page</a></p>
                  <p> Hu Zeng is currently an assistant professor at the College of Future Technology and the Center for Life Sciences at Peking University. He obtained his Ph.D. in Biochemistry and Molecular Biology from Peking University under the supervision of Professor Chengqi Yi, and subsequently conducted postdoctoral research at the Broad Institute of MIT and Harvard with Professor Xiao Wang. </p>
                  
                  
</td>
</tr>
</table>

<h2 align="center">Current Team Member</h2>



 <ul class="imgContainer">

    <li>
      <div class="imgWrap">
        <img src="http://127.0.0.1:4000/assets/img/team/cc.jpg" alt="">
      </div>
      <div class="content">
        <h4>Jie Ren(任杰)</h4>
      <p class="text-muted" style="font-size:90%;line-height: 1em;">Postdoctoral Fellow</p>
      <p style="font-size:90%">这里是第一张图片的描述文字。</p>
      <a href="https://github.com/ZenghuPKU" target="_blank"><i class="fa fa-github" aria-hidden="true"></i></a>
      <a href="mailto:huzeng@pku.edu.cn" target="_blank"><i class="fa fa-envelope" aria-hidden="true"></i></a>
      </div>
  </li>

   <li>
      <div class="imgWrap">
         <img src="{{site.baseurl}}/assets/img/team/test2.jpg" alt="Description of image 2">
      </div>
      <div class="content">
        <h4>Meng Tang (唐萌)</h4>
      <p class="text-muted" style="font-size:90%;line-height: 1em;">Lab Manager</p>
      <p style="font-size:90%">Graduated from Heriot-Watt University in the UK, lived in Europe and the United States for six years, and currently serves as the Administrative Secretary for Research at the Zenglab. Passionate about food and travel,</p>
      </div>
  </li>

   <li>
      <div class="imgWrap">
         <img src="{{site.baseurl}}/assets/img/team/cc.jpg" alt=" ">
      </div>
      <div class="content">
         <h4>Chen Cheng(程臣)</h4>
      <p class="text-muted" style="font-size:90%;line-height: 1em;">RA (incoming PhD student)</p>
      <p style="font-size:90%">MPhil Biomedical Science ,HKU</p>
      <p style="font-size:90%">Bsc biology, Double Major English literature, Zhejiang University</p>
      <a href="https://github.com/chengarthur" target="_blank"><i class="fa fa-github" aria-hidden="true"></i></a>
      <a href="mailto:zhizff74@connect.hku.hk" target="_blank"><i class="fa fa-envelope" aria-hidden="true"></i></a>
      </div>
  </li>

   <li>
      <div class="imgWrap">
        <img src="{{site.baseurl}}/assets/img/team/ye.jpg" alt="Description of image 2">
      </div>
      <div class="content">
       <h4>Lingyuan YE(叶凌源)</h4>
      <p class="text-muted" style="font-size:90%;line-height: 1em;">P</p>
      <p style="font-size:90%">Graduated from Heriot-Watt University in the UK, lived in Europe and the United States for six years, and currently serves as the Administrative Secretary for Research at the Zenglab. Passionate about food and travel,</p>
      </div>
  </li>
 </ul>



<!-- 
<table>
  <tr>
    <td class="img-cell">
      <img src="{{site.baseurl}}/assets/img/team/test1.jpg" alt=" ">
    </td>
    <td class="text-cell">
      <h4>Jie Ren(任杰)</h4>
      <p class="text-muted" style="font-size:90%;line-height: 1em;">Postdoctoral Fellow</p>
      <p style="font-size:90%">这里是第一张图片的描述文字。</p>
      <a href="https://github.com/ZenghuPKU" target="_blank"><i class="fa fa-github" aria-hidden="true"></i></a>
      <a href="mailto:huzeng@pku.edu.cn" target="_blank"><i class="fa fa-envelope" aria-hidden="true"></i></a>
    </td>
    <td class="img-cell">
      <img src="{{site.baseurl}}/assets/img/team/test2.jpg" alt="Description of image 2">
    </td>
    <td class="text-cell">
      <h4>Meng Tang (唐萌)</h4>
      <p class="text-muted" style="font-size:90%;line-height: 1em;">Lab Manager</p>
      <p style="font-size:90%">Graduated from Heriot-Watt University in the UK, lived in Europe and the United States for six years, and currently serves as the Administrative Secretary for Research at the Zenglab. Passionate about food and travel,</p>
    </td>
  </tr>
</table>
<table>
  <tr>
    <td class="img-cell">
      <img src="{{site.baseurl}}/assets/img/team/cc.jpg" alt=" ">
    </td>
    <td class="text-cell">
      <h4>Chen Cheng(程臣)</h4>
      <p class="text-muted" style="font-size:90%;line-height: 1em;">RA (incoming PhD student)</p>
      <p style="font-size:90%">MPhil Biomedical Science ,HKU</p>
      <p style="font-size:90%">Bsc biology, Double Major English literature, Zhejiang University</p>
      <a href="https://github.com/chengarthur" target="_blank"><i class="fa fa-github" aria-hidden="true"></i></a>
      <a href="mailto:zhizff74@connect.hku.hk" target="_blank"><i class="fa fa-envelope" aria-hidden="true"></i></a>
    </td>
    <td class="img-cell">
      <img src="{{site.baseurl}}/assets/img/team/ye.jpg" alt="Description of image 2">
    </td>
    <td class="text-cell">
      <h4>Lingyuan YE(叶凌源)</h4>
      <p class="text-muted" style="font-size:90%;line-height: 1em;">P</p>
      <p style="font-size:90%">Graduated from Heriot-Watt University in the UK, lived in Europe and the United States for six years, and currently serves as the Administrative Secretary for Research at the Zenglab. Passionate about food and travel,</p>
    </td>
  </tr>
</table>  -->