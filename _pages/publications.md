---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<html>
  <table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;">
          <tr onmouseout="nightsight_stop()" onmouseover="nightsight_start()">
            <td style="padding:20px;width:25%;vertical-align:middle;border-left-style:none;border-bottom-style:none;border-top-style:none;border-right-style:none">
              <img src="../images/rapidmapping.jpg" alt="hpp" style="border-style: none" >
            </td>
            <td style="padding:20px;width:75%;vertical-align:middle;border-left-style:none;border-bottom-style:none;border-top-style:none;border-right-style:none">
                <papertitle>Rapid-Mapping: LiDAR-Visual Implicit Neural Representations for Real-Time Dense Mapping
                </papertitle>
              <br> 
                Hanwen Zhang, Yujie Zou, Zhewen Yan, Hui Cheng
              <br>
              <em>IEEE Robotics and Automation Letters, 2024. </em><br>
            </td>
          </tr>
    </table>

</html>


<html>
    <table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;">
          <tr onmouseout="nightsight_stop()" onmouseover="nightsight_start()">
            <td style="padding:20px;width:50%;vertical-align:middle;border-left-style:none;border-bottom-style:none;border-top-style:none;border-right-style:none">
              <img src="../images/h2mapping.jpg" alt="hpp" style="border-style: none" >
            </td>
            <td style="padding:20px;width:75%;vertical-align:middle;border-left-style:none;border-bottom-style:none;border-top-style:none;border-right-style:none">
                <papertitle>H<sub>2</sub>-Mapping: Real-time Dense Mapping Using Hierarchical Hybrid Representation
                </papertitle>
              <br>
                Chenxing JIANG<sup>*</sup>, <strong>Hanwen Zhang</strong><sup>*</sup>, Peize Liu, Zehuan Yu, Hui Cheng, Boyu Zhou, Shaojie Shen
              <br>
              <em>* Co-first author. Orded Determined by coin flip.</em><br>
              <em>IEEE Robotics and Automation Letters, 2023. <strong><font color="red">(Best Paper Award)</font></strong> </em><br>
              <a href="https://ieeexplore.ieee.org/document/10243098"><img src="https://img.shields.io/badge/Paper-IEEE RAL-004088.svg"/></a>
              <a href="https://arxiv.org/abs/2306.03207"><img src="https://img.shields.io/badge/ArXiv-2306.03207-da282a.svg"/></a>
              <a href="https://github.com/SYSU-STAR/H2-Mapping">
              <img alt="Code" src="https://img.shields.io/github/stars/SYSU-STAR/H2-Mapping" />
              </a>
              <a href="https://youtu.be/oR9MlfL86Vw">
              <img alt="Youtube" src="https://img.shields.io/badge/Video-Youtube-red"/>
              </a>  
              <a href="https://www.bilibili.com/video/BV1Ku411W7j2">
              <img alt="Bilibili" src="https://img.shields.io/badge/Video-Bilibili-blue"/>
              </a>
              <a href="https://drive.google.com/file/d/1_3_lrniZDIiH1B2F-hmgppPkYpbj0ZHW/view?usp=sharing">
              <img alt="Revision" src="https://img.shields.io/badge/Paper-Revision-green.svg"/>
              </a>
            </td>
          </tr>
    </table>
    <!-- <table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;">
          <tr onmouseout="nightsight_stop()" onmouseover="nightsight_start()">
            <td style="padding:20px;width:25%;vertical-align:middle;border-left-style:none;border-bottom-style:none;border-top-style:none;border-right-style:none">
              <img src="../images/dido.png" alt="hpp" style="border-style: none" >
            </td>
            <td style="padding:20px;width:75%;vertical-align:middle;border-left-style:none;border-bottom-style:none;border-top-style:none;border-right-style:none">
                <papertitle>DIDO:Deep Inertial Quadrotor Dynamical Odometry
                </papertitle>
              <br>
                Kunyi Zhang, <strong>Chenxing Jiang</strong>, Jinghang Li, Sheng Yang, Teng Ma, Chao Xu, Fei Gao
              <br>
              <em>IEEE Robotics and Automation Letters, 2022.</em><br>
              <a href="https://ieeexplore.ieee.org/document/9817624"><img src="https://img.shields.io/badge/Paper-IEEE RAL-004088.svg"/></a>
              <a href="https://arxiv.org/abs/2203.03149"><img src="https://img.shields.io/badge/ArXiv-2203.03149-da282a.svg"/></a>
              <a href="https://github.com/zhangkunyi/DIDO">
              <img alt="Code" src="https://img.shields.io/github/stars/zhangkunyi/DIDO" />
              </a>
              <a href="https://www.bilibili.com/video/BV1dU4y1Z773?spm_id_from=333.999.0.0">
              <img alt="Bilibili" src="https://img.shields.io/badge/Video-Bilibili-blue"/>
              </a>
            </td>
          </tr>
    </table> -->
</html>


{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;">
          <tr onmouseout="nightsight_stop()" onmouseover="nightsight_start()">
            <td style="padding:20px;width:25%;vertical-align:middle;border-left-style:none;border-bottom-style:none;border-top-style:none;border-right-style:none">
              <img src="../images/h2mapping.jpg" alt="hpp" style="border-style: none" >
            </td>
            <td style="padding:20px;width:75%;vertical-align:middle;border-left-style:none;border-bottom-style:none;border-top-style:none;border-right-style:none">
                <papertitle>H2-Mapping: Real-time Dense Mapping Using Hierarchical Hybrid Representation
                </papertitle>
              <br>
                Chenxing JIANG, <strong>Hanwen Zhang</strong>, Peize Liu, Zehuan Yu, Hui Cheng, Boyu Zhou, Shaojie Shen
              <br>
              <em>aaa</em><br>
              <em>IEEE Robotics and Automation Letters, 2023. <strong><font color="red">(Best Paper Award)</font></strong> </em><br>
              <a href="https://ieeexplore.ieee.org/document/10243098"><img src="https://img.shields.io/badge/Paper-IEEE RAL-004088.svg"/></a>
              <a href="https://arxiv.org/abs/2306.03207"><img src="https://img.shields.io/badge/ArXiv-2306.03207-da282a.svg"/></a>
              <a href="https://github.com/SYSU-STAR/H2-Mapping">
              <img alt="Code" src="https://img.shields.io/github/stars/SYSU-STAR/H2-Mapping" />
              </a>
              <a href="https://youtu.be/oR9MlfL86Vw">
              <img alt="Youtube" src="https://img.shields.io/badge/Video-Youtube-red"/>
              </a>  
              <a href="https://www.bilibili.com/video/BV1Ku411W7j2">
              <img alt="Bilibili" src="https://img.shields.io/badge/Video-Bilibili-blue"/>
              </a>
              <a href="https://drive.google.com/file/d/1_3_lrniZDIiH1B2F-hmgppPkYpbj0ZHW/view?usp=sharing">
              <img alt="Revision" src="https://img.shields.io/badge/Paper-Revision-green.svg"/>
              </a>
            </td>
          </tr>
    </table>
