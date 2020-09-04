# 3D打印技术之选择性激光烧结技术（SLS）
#### 摘要：
本文主要对先进制造技术的选择性激光烧结技术（SLS）进行了学习和认识，SLS技术起源于美国1986年，是3D打印技术的一种。选择性激光烧结技术借助于计算机辅助设计与制造，采用分层制造叠加原理，将固体粉末直接成形为三维实体零件，其具有原料广泛、制作工艺简单、周期短等特点，现已大量商用，在诸多领域得到了广泛的应用。
## 前言
   3D 打印技术，学术上又称“添加制造” ( additive manufacturing) 技术，也称增材制造或增量制造。3D 打印技术作为第三次工业革命的代表性技术之一，也作为工业4.0与智能制造的代表技术之一，是一种较为先进的制造技术。
   目前，已实现商品化的3D打印以熔融沉积式 (FDM）、光固化打印( SLA)、 选择性激光烧结（SLS）、选择性激光熔化成型(SLM)等等为主。其中我们合工大工程训练中心的创客空间里面的小型3D打印机都是熔融沉积式 (FDM），熔融沉积式主要是价格低廉但是制造精度不高。我们这一篇文章主要介绍选择性激光烧结（SLS），选择性激光烧结(SLS)是发展最快、最为成功的快速成型方法之一,采用该技术不仅可以制造出精确的模型和原型,还可以成型具有可靠结构的金属零件。由于其具有诸多优点,如粉末选材广泛、适用性广,可直接烧结零件等,因此在现代制造业中受到越来越广泛的重视。
## 选择性激光烧结技术的发展及研究概括
   选择性激光烧结技术起源于美国德克萨斯大学澳斯汀分校（University of Texas at Austin）。1986年，该校学者Carl Deckard在其硕士论文中首次提出了选择性激光烧结技术工艺原理，于1988年研制成功了第一台选择性激光烧结技术成形机。随后，由美国的DTM公司将其商业化，于1992年推出了该工艺的商业化生产设备Sinter Station 2000成形机。在过去的20多年里，选择性激光烧结技术在各个领域得到了广泛的应用，各国研究人员对选择性激光烧结技术从基本形成原理、加工工艺、新材料、精度控制、数值仿真等方面进行了广泛而深入的研究，有力地推动了选择性激光烧结工艺的发展。
    我国从90年代就已经开展选择性激光烧结工艺的相关研究工作，国内有多家从事研究选择性激光烧结系统以及相适 用材料的学校及研究所，并且在诸多方面取得令人瞩目 的成就。2000年北京隆源成功研制出复杂内腔金属零件的快速铸造工艺；2009 年开发出铸造覆膜砂烧结成型的专业设备，并成功用于汽车发动机缸体和缸盖的快速开发；2011年华曙高科成功研制出我国首台选择性激光烧结设备 FS401α机，使我国成为继美国 3Dsystems、德国 EOS外，世界上第三家高端选择性激光烧结设备制造商。 2012年华曙高科成功研制出PA3-C尼龙材料，使我国成为世界上第二家尼龙材料的制造商。华中科技大学快速成形中心长期以来一直进行快速成形装备、工艺以及材料方面的研究。经过多年的研究，成功开发出一系列选择性激光烧结系统。
## 选择性激光烧结技术工艺原理
选择性激光加工是以CO2 激光器为能源，利用计算机控制红外激光束对非金属粉末、金属粉末或 复合物的粉末薄层，以一定的速度和能量密度按分层面的二维数据进行扫描烧结，层层堆积，最后形成成形件。其工艺原理框图，如图1所示：（图片来源：参考文献[3]）
 
整个工艺装置由粉末缸（Powder Cylinder）、成型缸（Model Cylinder）、激光器、计算机控制系统四部分组成。工作时，粉末缸活塞（送粉活塞）上升，先在基体上用滚筒均匀铺上一薄层金属粉末，并将其加热至略低于材料熔点，以减少热变形，并利于与前一层面的结合。然后，激光束在计算机控制光路系统的精确引导下，按照零件的分层轮廓有选择地进行烧结，使材料粉末烧结或熔化后凝固形成零件的一个层面，没有烧过的地方仍保持粉末状态,并可作为有悬臂的微结构下一层烧结的支撑。烧结完一层后，基体下移一个截面层厚，铺粉系统铺设新粉,计算机控制激光束再 次扫描进行下一层的烧结。如此循环，层层叠加，就得到三维零件。最后，将未烧结的粉末回收到粉末缸中，取出成型件，再进行打磨、烘干等后处理工艺，最终形成满足要求的原形或制件。
## 选择性激光烧结技术的特点
选择性激光烧结技术相比于传统的制造技术，其具有显著优点。
①	过程与零件复杂程度无关，是真正的自由制造，这是传统方法无法比拟的。选择性激光烧结技术与其它制造工艺不同，不需要预先制作支架，未烧结的松散粉末作了自然支架。选择性激光烧结技术可以成型几乎任意几何形状的零件，对具有复杂内部结构的零件特别有效。
②	产品的单价几乎与批量无关，特别适合于新产品的开发或单件、小批量零件的生产，也适合与最近几年兴起的私人定制产品。
③	生产周期短，从CAD设计到零件的加工完成只需几小时到几十小时，整个生产过程数字化，可随时修正、随时制造。这一特点使其特别适合于新产品的开发。
④	可使用的材料范围宽，从理论上来说，任何受热后能够粘结的粉末都可以用作选择性激光烧结的原材，如塑料、石蜡、金属、陶瓷等。材料无浪费，未烧结的粉末可重复使用。
## 选择性激光烧结技术的实际应用
选择性激光烧结技术的实际应用范围非常广泛，其己经成功应用于汽车、造船、航天、航空、通讯、微机电系统、建筑、医疗、考古等诸多行业，为许多传统制造业注入了新的创造力，也带来了信息化的气息。概括来说，选择性激光烧结技术可以应用于以下场合：
①快速原型制造。选择性激光烧结技术可快速制造所设计零件的原形，并对产品及时进行评价、修正以提高设计质量。
②新型材料的制备及研发。利用选择性激光烧结技术可以开发一些新型的颗粒以增强复合材料和硬质合金。 
③在医学上的应用。选择性激光烧结技术实现生物医用材料、人造肢体及医用植入体的个性化设计和生产,并且具有很少的工序环节和很短的加工周期,因此在生物医用材料的制备领域具有重大应用价值。
④小批量、特殊零件的制造加工。在制造业领域，经常遇到小批量及特殊零件的生产。这类零件加工周期长，成本高，对于某些形状复杂零件，甚至无法制造。采用选择性激光烧结技术可经济地实现小批 量和形状复杂零件的制造。 
⑤快速模具和工具制造。选择性激光烧结技术制造的零件可直接作为模具使用，如熔模铸造、砂型铸造、注塑模型、高精度形状复杂的金属模型等；也可以将成形件经后处理后作为功能零件使用。
<center>*参考文献*</center>
[1]李小丽,马剑雄,李萍,陈琪,周伟民.3D打印技术及应用趋势[J].自动化仪表,2014,35(01):1-5.
[2]李鹏,熊惟皓.选择性激光烧结的原理及应用[J].材料导报,2002(06):55-58.
[3]任继文,彭蓓.选择性激光烧结技术的研究现状与展望[J].机械设计与制造,2009(10):266-268.
[4]潘琰峰,沈以赴,顾冬冬,胥橙庭.选择性激光烧结技术的发展现状[J].工具技术,2004(06):3-7.
[5]白培康.选择性激光烧结快速成型技术研究及应用现状[J].航空制造技术,2009(03):51-53. 
[6]闫春泽. 聚合物及其复合粉末的制备与选择性激光烧结成形研究[D].华中科技大学,2009.
[7]徐林. 碳纤维/尼龙12复合粉末的制备与选择性激光烧结成形[D].华中科技大学,2009.
[8]黄卫东,吕晓卫,林鑫.激光成形制备生物医用材料研究现状与发展趋势[J].中国材料进展,2011,30(04):1-10+29.




## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/kanhao100/kanhao100.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
![baidu](https://www.baidu.com/img/PCfb_5bf082d29588c07f842ccde3f97243ea.png)
```
# Just testing_20200904
[baidu](https://www.baidu.com/img/PCfb_5bf082d29588c07f842ccde3f97243ea.png)
![baidu](https://www.baidu.com/img/PCfb_5bf082d29588c07f842ccde3f97243ea.png)

![test_picture](https://github.com/kanhao100/kanhao100.github.io/blob/master/picture/test.jpg)
For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

## test Header 2

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/kanhao100/kanhao100.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
