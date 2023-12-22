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

![gif1](docs/1.gif) | ![gif2](docs/2.gif) | ![gif3](docs/3.gif)

![figure1](docs/1.jpg)
![figure2](docs/2.jpg)
![figure3](docs/3.jpg)

![gif4](docs/4.gif) | ![figure4](docs/4.jpg)

# Method

The framework consists of two main components: Geometric Consistency and Style Consistency.
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
![gif5](docs/5.gif) | ![gif6](docs/6.gif)
![Link to Figure 7](docs/7.png)
![Link to gif7](docs/7.gif) | ![Link to gif8](docs/8.gif)

# Contact Us

Email: business@aidlab.tech
![Link to Figure 8](docs/8.jpg) | ![Link to Figure 9](docs/9.jpg)

