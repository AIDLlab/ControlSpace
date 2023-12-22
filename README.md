# ControlSpace
**<span style="color:red">
News</span>**: Demo： <a href = "https://labs.jianchuang.tech">简创实验室</a> ( for Chinese users ) . Although the interface is not currently open, it will be online as soon as possible

<font color='red'>**News:**</font>
For a full introduction, please visit <a href = 'https://mp.weixin.qq.com/s?__biz=MzU2NDk5OTk3Mw==&mid=2247484009&idx=1&sn=256588cad735074642cdb7f00595e40b&chksm=fc432023cb34a93558c1672bea3698081773bf7decbc553c98abd85daf6156cd051f438227b7#rd' >发布 | ControlSpace空间多视角一致性图像生成框架，刷新AIGC设计应用SOTA</a>.

<font color='red'>**Note: Please don't forget to give us a star if you like this project. Thanks!**</font> :stuck_out_tongue_winking_eye:

---


[//]: # (~~**A demo that can be experienced is being prepared.**~~)

ControlSpace: Multi-view consistent image generation framework, updated the AIGC design application SOTA

Institute for AID Lab

<a href='https://github.com/AIDLlab/ControlSpace/'><img src='https://img.shields.io/badge/Project-Page-Green'></a> 

# Demo

<div style="display: flex; justify-content: space-between;">
    <img src="docs/1.gif" alt="gif1" width="30%">
    <img src="docs/2.gif" alt="gif2" width="30%">
    <img src="docs/3.gif" alt="gif3" width="30%">
</div>

<div style="display: flex; justify-content: space-between;">
    <img src="docs/4.gif" alt="gif4" width="29.6%">
    <img src="docs/4.png" alt="figure4" width="60.4%">
</div>

<br> <!-- 插入一行间距 -->

<div style="display: flex; justify-content: space-between;">
    <img src="docs/3.png" alt="figure3" width="90%">
</div>

<br> <!-- 插入一行间距 -->

<div style="display: flex; justify-content: space-between;">  
    <img src="docs/1.png" alt="figure1" width="90%">
    <img src="docs/2.png" alt="figure2" width="90%">
</div>



# Method

The framework consists of two main components: Geometric Consistency and Style Consistency.

<br> <!-- 插入一行间距 -->

![Link to Figure 5](docs/5.png)

**Geometric Consistency**

The geometric consistency part involves techniques such as iterative alignment strategies and alignment-aware training strategies to establish geometric priors on Nerf/Mip-Nerf models (AGP).

**Style Consistency**

The style consistency component employs cross-frame non-local attention modules to address frame alignment issues.

# Performance Evaluation

The Control Space framework demonstrates a significant advantage in terms of consistency when compared to generating multiple images through ControlNet individually.

![Link to Figure 6](docs/6.png)

# Future Developments

Our future work aims to enhance the controllability of 3D scenes based on the Control Space framework.

<div style="display: flex; justify-content: space-between;">
    <img src="docs/5.gif" alt="gif5" width="45%">
    <img src="docs/6.gif" alt="gif6" width="45%">
</div>

<div style="display: flex; width: 100%;">
  <div style="width: 50%;">
    <img src="docs/7.png" style="width: 100%; height: auto;">
  </div>
  <div style="width: 50%; display: flex; flex-direction: column; justify-content: center;">
    <div style="margin-bottom: 10px;"> <!-- Add margin for spacing between the two images -->
      <img src="docs/7.gif" style="width: 100%; height: auto;">
    </div>
    <div>
      <img src="docs/8.gif" style="width: 100%; height: auto;">
    </div>
  </div>
</div>


# Contact Us

Email: business@aidlab.tech

<div style="display: flex;">
    <img src="docs/8.jpg" alt="Link to Figure 8" width="23%">

