## 关于迁移学习的一些资料，以后会在这里更新

### 1.迁移学习简介

[文档](https://github.com/jindongwang/transferlearning/blob/master/doc/%E8%BF%81%E7%A7%BB%E5%AD%A6%E4%B9%A0%E7%AE%80%E4%BB%8B.md)   ||   [PPT(英文)](https://github.com/jindongwang/transferlearning/blob/master/doc/TransferLearning.pdf)   ||  [PPT(中文)](https://github.com/jindongwang/transferlearning/blob/master/doc/%E8%BF%81%E7%A7%BB%E5%AD%A6%E4%B9%A0_zh-cn.pdf)

- - -

### 2.迁移学习的综述文章

[一些迁移学习的综述文章](https://github.com/jindongwang/transferlearning/tree/master/paper/survey)，中文英文都有。

- 其中，代表性的综述是[A survey on transfer learning](https://github.com/jindongwang/transferlearning/blob/master/paper/survey/A%20survey%20on%20transfer%20learning_Pan_Yang_2010.pdf)，这是最具代表性的综述，对迁移学习进行了比较权威的定义。

- 最新的综述是[A survey of transfer learning](https://github.com/jindongwang/transferlearning/blob/master/paper/survey/A%20survey%20of%20transfer%20learning_Weiss%20et%20al_2016.pdf)，写于2015-2016年。其中交代了一些比较经典的如同构、异构等学习方法代表性文章。包括了很多方法介绍，值得一看。

- 此外，还包括[迁移学习应用于行为识别](https://github.com/jindongwang/transferlearning/blob/master/paper/survey/Transfer%20learning%20for%20activity%20recognition%20-%20a%20survey_Cook%20et%20al_2013.pdf)、[迁移学习与增强学习](https://github.com/jindongwang/transferlearning/blob/master/paper/survey/Transfer%20Learning%20for%20Reinforcement%20Learning%20Domains_Taylor_Stone_2009.pdf)结合等。中文方面，[迁移学习研究进展](https://github.com/jindongwang/transferlearning/blob/master/paper/survey/%E8%BF%81%E7%A7%BB%E5%AD%A6%E4%B9%A0%E7%A0%94%E7%A9%B6%E8%BF%9B%E5%B1%95_Zhuang%20et%20al_2010.pdf)是一篇不错的中文综述。


- - -

### 3.代码

#### - Matlab：[domain adaptation toolbox](https://github.com/viggin/domain-adaptation-toolbox)

这是一份用matlab写的domain adaptation工具包，内包含了以下的9种迁移学习方法。

![Matlab](https://raw.githubusercontent.com/jindongwang/transferlearning/master/png/matlab.png)

#### - Python：[我写的工具包](https://github.com/jindongwang/transferlearning/tree/master/code/python)

**我写的python版本工具包，目前刚完成了transfer component analysis （TCA）方法。也请有意愿的同学来一起加入这个项目。**


- - -

### 4.迁移学习代表性研究学者

- [Qiang Yang](http://www.cs.ust.hk/~qyang/)：中文名杨强。香港科技大学计算机系主任，教授，大数据中心主任。迁移学习领域世界性专家。IEEE/AAAI/IAPR/AAAS fellow。[[Google scholar](https://scholar.google.com/citations?user=1LxWZLQAAAAJ&hl=zh-CN)]
- [Sinno Jialin Pan](http://www.ntu.edu.sg/home/sinnopan/)：杨强的学生，香港科技大学博士，现任新加坡南阳理工大学助理教授。迁移学习领域代表性综述A survey on transfer learning的第一作者（Qiang Yang是二作）。[[Google scholar](https://scholar.google.com/citations?user=P6WcnfkAAAAJ&hl=zh-CN)]
- [Fuzhen Zhuang](http://www.intsci.ac.cn/users/zhuangfuzhen/)：中文名庄福振，中科院计算所博士，现任中科院计算所副研究员。[[Google scholar](https://scholar.google.com/citations?user=klJBYrAAAAAJ&hl=zh-CN&oi=ao)]
- [Mingsheng Long](http://ise.thss.tsinghua.edu.cn/~mlong/)：中文名龙明盛，清华大学博士，现任清华大学助理研究员。[[Google scholar](https://scholar.google.com/citations?view_op=search_authors&mauthors=mingsheng+long&hl=zh-CN&oi=ao)]
- [Lixin Duan](ttp://www.lxduan.info/)：中文名段立新，现任亚马逊高级科学家。

- - -

### 5.迁移学习相关的硕博士论文

包括了中英文的一些迁移学习相关的硕博士论文。其中，诸如杨强的学生，像

- [Sinno Jialin Pan](https://github.com/jindongwang/transferlearning/blob/master/paper/%E7%A1%95%E5%8D%9A%E5%A3%AB%E8%AE%BA%E6%96%87/%5BPhDThesis10%5DFeature-based%20Transfer%20Learning%20with%20Real-world%20Applications.pdf_.pdf)
- [Hao Hu](https://github.com/jindongwang/transferlearning/blob/master/paper/%E7%A1%95%E5%8D%9A%E5%A3%AB%E8%AE%BA%E6%96%87/Learning-based%20Human%20activity%20recognition.pdf_.pdf)
- [Wenchen Zheng](https://github.com/jindongwang/transferlearning/blob/master/paper/%E7%A1%95%E5%8D%9A%E5%A3%AB%E8%AE%BA%E6%96%87/Learning%20with%20Limited%20Data%20in%20Sensor-based%20Human%20Behavior%20Perdiction.pdf_.pdf)

等的博士论文都是关于迁移学习的。中文方面，

- 中科院计算所[赵中堂](https://github.com/jindongwang/transferlearning/blob/master/paper/%E7%A1%95%E5%8D%9A%E5%A3%AB%E8%AE%BA%E6%96%87/%E8%87%AA%E9%80%82%E5%BA%94%E8%A1%8C%E4%B8%BA%E8%AF%86%E5%88%AB%E4%B8%AD%E7%9A%84%E8%BF%81%E7%A7%BB%E5%AD%A6%E4%B9%A0%E6%96%B9%E6%B3%95%E7%A0%94%E7%A9%B6_%E8%B5%B5%E4%B8%AD%E5%A0%82.pdf_.pdf)
- 清华大学[龙明盛](https://github.com/jindongwang/transferlearning/blob/master/paper/%E7%A1%95%E5%8D%9A%E5%A3%AB%E8%AE%BA%E6%96%87/%E8%BF%81%E7%A7%BB%E5%AD%A6%E4%B9%A0%E9%97%AE%E9%A2%98%E4%B8%8E%E6%96%B9%E6%B3%95%E7%A0%94%E7%A9%B6_%E9%BE%99%E6%98%8E%E7%9B%9B_.pdf)
- 以及上海交通大学的[戴文渊](https://github.com/jindongwang/transferlearning/blob/master/paper/%E7%A1%95%E5%8D%9A%E5%A3%AB%E8%AE%BA%E6%96%87/%E5%9F%BA%E4%BA%8E%E5%AE%9E%E4%BE%8B%E5%92%8C%E7%89%B9%E5%BE%81%E7%9A%84%E8%BF%81%E7%A7%BB%E5%AD%A6%E4%B9%A0%E7%AE%97%E6%B3%95%E7%A0%94%E7%A9%B6_%E6%88%B4%E6%96%87%E6%B8%8A.caj)是比较代表性的文章。

其他的文章，请见[完整版](https://github.com/jindongwang/transferlearning/tree/master/paper/%E7%A1%95%E5%8D%9A%E5%A3%AB%E8%AE%BA%E6%96%87)。

- - -

### [记与迁移学习大牛杨强教授的第二次会面](https://zhuanlan.zhihu.com/p/26260083)

- - -


### 未来计划：

迁移学习、transfer learning、domain adaptation眹的我看过的一些论文

以及我已经写好的一些总结