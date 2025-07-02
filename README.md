# industry_algo

## Roadmap 0: roadmap of roadmap
广告算法资料汇总【建设中】 - 广告与算法的文章 - 知乎
https://zhuanlan.zhihu.com/p/665111976

## Roadmap 1: Alibaba

我们之前一直聚焦用户的序列行为挖掘，DIN/DIEN/MIMN/SIM等兴趣模型本质上是我们对“用户兴趣”这个物理概念进行的数学化解析，我称之为“物理式先验建模”
Their work: DIN/DIEN/MIMN/SIM

而除了兴趣建模外业界还有另外一个方向，如PNN、DeepFM、DCN等，这些模型也在特定的场景被广泛使用。相比兴趣模型而言这些模型本质上是基于人的先验认识，通过模型的结构设计捕捉特征之间的"代数关系"，这个流派我称之为“代数式先验建模”。
Their work: CAN/STAR

精排模型DIN/DIEN/SIM/DFN/DCIN

From 屠龙少年与龙：漫谈深度学习驱动的广告推荐技术发展周期 - 朱小强的文章 - 知乎
https://zhuanlan.zhihu.com/p/398041971
https://zhuanlan.zhihu.com/p/674125085

## Roadmap 2: Alibaba

lr、deepfm仍然是短平快的首选，多目标就上mmoe，谈序列就上din

召回模型还是双塔及其变种，但数据量少的业务双塔都搭不起来；itemcf、swing、eges仍然是不可或缺的主力

如果我觉得特征交叉程度不够，我在底层再凑一个masknet

如果有具体消偏需求，我再用偏差特征另起一个小网络，与正常特征再叉一遍

推荐系统领域虽然论文越来越fancy，但是业界用的最多的baseline模型大概是哪些呢？ - 严武小虎的回答 - 知乎
https://www.zhihu.com/question/9469687994/answer/120151678412
