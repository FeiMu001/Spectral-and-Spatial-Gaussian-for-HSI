<div align=center class="logo">
<img src="figs/logo.png" style="width:640px; margin: 0; padding: 0; display: block;">

# S²Gaussian: Explicit Continuous Spatial-Spectral Representation for Hyperspectral Images

#### [Fei Mu](), [Junjun Jiang<sup>*</sup>](https://homepage.hit.edu.cn/jiangjunjun), [Zengyuan Zuo](), [Kui Jiang](https://homepage.hit.edu.cn/jiangkui), and [Xianming Liu](https://homepage.hit.edu.cn/xmliu)

###### <sup>*</sup> Corresponding Author

[AIIA Lab](https://aiialabhit.github.io/team/), Harbin Institute of Technology.

[![paper](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)]()
![GitHub Repo stars](https://img.shields.io/github/stars/FeiMu001/Spectral-and-Spatial-Gaussian?style=social)
</div>

## 🔥 News

- ☐ Release our code, pretrained models, welcome to test the performance.
- ☐ Release our [manuscript]().
- **2026.1.9**: ✅ This repo is created.

<!-- ## 📋 Overview 
<div align="center"> <table> <tr> <td align="center"><img src="figs/1.png" width="255"><br>Comparison</td> <td align="center"><img src="figs/2.png" width="425"><br>Workflow</td> </tr> </table> </div>

## 📝 Abstract
Implicit Neural Representations (INRs) achieve strong performance in hyperspectral image (HSI) representation but suffer from excessive training memory consumption, low inference efficiency, and poor interpretability, while 2D Gaussian Splatting (2DGS)–an advanced explicit continuous representation technique for natural images–alleviates these limitations via efficient and interpretable modeling yet focuses solely on spatial continuity, rendering it incompatible with HSIs that require joint spatial-spectral modeling. To bridge this gap, we first develop a 2DGS-based mathematical model for continuous spatial-spectral modeling of HSI, and further propose Spectral and Spatial Gaussian (S2Gaussian) via equivalent decoupling, an explicit continuous spatial-spectral representation framework tailored for HSI with two core components: Spectral Gaussian, which employs 1D Gaussian primitives to enable continuous spectral representation, and Spatial Gaussian, which adopts 2D Gaussian primitives to achieve continuous spatial representation for arbitrary bands while preserving fine-grained spatial details. To mitigate the prohibitive computational complexity of naive 2DGS-based modeling for large-sized, high-dimensional HSIs, we further introduce two key optimizations–a grouping strategy that reduces model parameters by partitioning HSIs into manageable subgroups and a prior-guided parameter pre-training scheme that leverages Global Spectral Prior for Spectral Gaussian and Maximum-Entropy Band Prior for Spatial Gaussian to accelerate convergence and enhance modeling accuracy. Extensive experiments validate S2Gaussian’s exceptional performance: it achieves state-of-the-art (SOTA) results in continuous representation tasks and delivers satisfactory performance in downstream compression tasks.

## 📊 Results
<details>
<summary><strong>Continuous Representation for CHIKUSEI HSI across different methods</strong> (click to expand) </summary>

<img src = "figs/representation1.png"> 
</details>

<details>
<summary><strong>Continuous Representation for HOUSTON 2018 HSI across different methods</strong> (click to expand) </summary>

<img src = "figs/representation2.png"> 
</details>

<details>
<summary><strong>CHIKUSEI HSI compression across different methods</strong> (click to expand) </summary>
<img src = "figs/compression1.png"> 
</details>

<details>
<summary><strong>PAVIA CENTRE HSI compression across different methods</strong> (click to expand) </summary>

<img src = "figs/compression2.png"> 
</details>

## 👁️ Visual Comparisons
<details>
<summary><strong>Continuous Representation Result for the Chikusei Dataset</strong> (click to expand) </summary>

<img src = "figs/visual1.png"> 
</details>

<details>
<summary><strong>Continuous Representation Result for theHouston 2018 HSI Dataset</strong> (click to expand) </summary>

<img src = "figs/visual2.png"> 
</details>

<details>
<summary><strong>Compression Results for the Chikusei Dataset</strong> (click to expand) </summary>

<img src = "figs/visual3.png"> 
</details>

<details>
<summary><strong>Compression Results for the Pavia Centre Dataset</strong> (click to expand) </summary>

<img src = "figs/visual4.png"> 
</details>

## 📖 Citation 
```

``` -->
## 📧 Contact
If you have any questions, please contact the email <mufei970217@163.com> or <3565741165@qq.com>.