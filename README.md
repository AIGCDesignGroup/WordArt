
# 创意艺术字设计 （WordArt Designer）
<div align="center">
  <img src='assert/banner.png' width='900'/>
</div>

## 模型描述
**创意艺术字设计** （WordArt Designer）是一个基于用户驱动，依赖于大型语言模型(LLMs)的艺术字生成框架系统。该系统包含四个关键模块:LLM引擎、SemTypo、Stlytypo和TextTypo模块。由通义千问驱动的LLM引擎可以解释用户输入，并为其他模块生成可操作的提示，从而将抽象概念转化为有形的设计。SemTypo模块使用语义概念优化字体设计，在艺术转换和可读性之间取得平衡。在SemTypo模块提供的语义布局的基础上，StyTypo模块辅助生成平滑、精细的图像。TextTypo模块通过纹理渲染进一步增强了设计的美观性，能够生成创造性的纹理字体。值得注意的是，WordArt Designer已经成功地在电子商务平台实施，用于创建横幅和海报，这体现了人工智能在增强艺术字体排版方面的潜力。创意艺术字设计 创空间试用 Link：https://modelscope.cn/studios/WordArt/WordArt/summary
（**目前已经在Modelscope上完成开源，代码体验链接： https://modelscope.cn/models/jyhe21/wordart_designer/summary**）



<div align="center">
  <img src='assert/intro.png' width='900'/>
  <br>
  <i>图 1: WordArt Designer 交互方式示意.</i>
</div>



<div align="center">
  <img src='assert/framework.png' width='900'/>
  <br>
  <i>图 1: WordArt Designer 系统框架.</i>
</div>




## Citation
如果这个工作对你有用,请引用以下文章:

```bibtex
@misc{he2023wordart,
      title={wordart designer: user-driven artistic typography synthesis using large language models}, 
      author={Jun-Yan He and Zhi-Qi Cheng and Chenyang Li and jingdong Sun and Wangmeng Xiang and Xianhui Lin, and Xiaoyang Kang and Zengke Jin and Yusen Hu and Bin Luo and Yifeng Geng and Xuansong Xie and Jingren Zhou},
      year={2023},
      eprint={2310.18332},
      primaryClass={cs.CV}
}

@misc{he2024wordartapi,
      title={wordart designer API: User-Driven Artistic Typography Synthesis with Large Language Models on ModelScope}, 
      author={Jun-Yan He and Zhi-Qi Cheng and Chenyang Li and jingdong Sun and Wangmeng Xiang and Xianhui Lin, and Xiaoyang Kang and Zengke Jin and Yusen Hu and Bin Luo and Yifeng Geng and Xuansong Xie and Jingren Zhou},
      year={2024},
      eprint={2401.01699},
      primaryClass={cs.CV}
}
```