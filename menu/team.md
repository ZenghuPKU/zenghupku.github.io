---
layout: page
title: Team
permalink: /team
---

<style>
  .imgContainer {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    padding: 0; /* Remove default padding */
  }
  .imgContainer li {
    list-style: none;
    width: calc(50% - 10px); /* Adjust width for two columns */
    margin: 20px 0; /* Adjust margin between items */
    box-shadow: 0px 0px 2px 0px #999;
    padding: 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
  }
  .imgContainer li:hover {
    box-shadow: 0px 0px 5px 0px #999;
    transition: .5s;
  }
  .imgContainer .imgWrap {
    width: 100%;
    height: 400px; /* Fixed image height */
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden;
  }
  .imgContainer .imgWrap img {
    width: auto;
    height: 100%;
    object-fit: cover; /* Ensure image fills the container */
  }
  .imgContainer li .content {
    width: 100%;
    padding: 20px;
  }
  .imgContainer li .content h4 {
    margin: 0;
    line-height: 1.5em;
  }
  .imgContainer li .content p {
    line-height: 1.5em;
    font-size: 90%;
  }

  /* Media query for responsiveness */
  @media (max-width: 768px) {
    .imgContainer li {
      width: 100%; /* Full width on smaller screens */
    }
  }
</style>

<h2 align="center">Group Leader</h2>
<table>
  <tr>
    <td class="img-cell">
      <img src="{{site.baseurl}}/assets/img/team/hunew.jpeg" width="800px"/>
    </td>
    <td class="text-cell">
      <h4>Hu Zeng (曾虎)</h4>
      <p class="text-muted" style="font-size:90%;line-height: 1em;">Assistant Professor for life science at Peking University</p>
      <p style="font-size:90%">Email: huzeng@pku.edu.cn<a href="mailto:huzeng@pku.edu.cn" target="_blank"><i class="fa fa-envelope" aria-hidden="true"></i></a>
        <br>Tel: +86 (010) 62767687<br>
        <a href="https://future.pku.edu.cn/jsdw/jy/fzyxs1/11e271c0c09e4b919554a49d90093b98.htm" target="_blank">CFT PI page</a> |
        <a href="https://www.cls.edu.cn/PrincipalInvestigator/pi/index6199.shtml" target="_blank">CLS PI page</a></p>
      <p>Hu Zeng is currently an assistant professor at the College of Future Technology and the Center for Life Sciences at Peking University. He obtained his Ph.D. in Biochemistry and Molecular Biology from Peking University under the supervision of Professor Chengqi Yi, and subsequently conducted postdoctoral research at the Broad Institute of MIT and Harvard with Professor Xiao Wang.</p>
    </td>
  </tr>
</table>

<h2 align="center">Current Team Members</h2>

<div class="imgContainer">
  <!-- Left Column -->
  <ul>
    <li>
      <div class="imgWrap">
        <img src="{{site.baseurl}}/assets/img/team/renjie.jpg" alt="">
      </div>
      <div class="content">
        <h4>Jie Ren(任杰)</h4>
        <p class="text-muted" style="font-size:90%;line-height: 1em;">Postdoctoral Fellow</p>
        <p style="font-size:90%">PhD, Biology, Peking University</p>
        <p style="font-size:90%">Bsc, Biology, China Agricultural University</p>
        <a href="mailto:renjie@pku.edu.cn" target="_blank"><i class="fa fa-envelope" aria-hidden="true"></i></a>
      </div>
    </li>

    <!-- Add more team members as needed -->
  </ul>

  <!-- Right Column -->
  <ul>
    <li>
      <div class="imgWrap">
        <img src="{{site.baseurl}}/assets/img/team/tangmengnew.jpg" alt="">
      </div>
      <div class="content">
        <h4>Meng Tang (唐萌)</h4>
        <p class="text-muted" style="font-size:90%;line-height: 1em;">Lab Manager</p>
        <p style="font-size:90%">Graduated from Heriot-Watt University in the UK, lived in Europe and the United States for many years, and currently serves as the Administrative Secretary for Research at the Zenglab.</p>
      </div>
    </li>

    <!-- Add more team members as needed -->
  </ul>
</div>
