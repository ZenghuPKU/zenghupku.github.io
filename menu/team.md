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
        width: auto; /* 图片宽度自适应单元格 */
        height: 400px;
        object-fit: cover;
    }
    .text-cell {
        width: 25%; /* 分配25%宽度给文字 */
    }

    .imgContainer {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
    }
    .imgContainer li {
        list-style: none;
        width: 48%; /* 修改为48%以便两列排列 */
        margin: 20px 1%;
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
        height: 400px; /* 固定图片高度 */
        display: flex;
        justify-content: center;
        align-items: center;
        overflow: hidden;
    }
    .imgContainer .imgWrap img {
        width: auto;
        height: 100%;
        object-fit: cover; /* 确保图片按比例填充 */
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

<h2 align="center">Current Team Member</h2>

<ul class="imgContainer">
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

    <li>
        <div class="imgWrap">
            <img src="{{site.baseurl}}/assets/img/team/tangmengnew.jpg" alt="Description of image 2">
        </div>
        <div class="content">
            <h4>Meng Tang (唐萌)</h4>
            <p class="text-muted" style="font-size:90%;line-height: 1em;">Lab Manager</p>
            <p style="font-size:90%">Graduated from Heriot-Watt University in the UK, lived in Europe and the United States for many years, and currently serves as the Administrative Secretary for Research at the Zenglab.</p>
        </div>
    </li>
</ul>
