# 基于图像的水稻穗粒相关性状智能检测算法

王栋<sup>1,2</sup>, 陈佳玮<sup>1,2</sup>, 沈利言<sup>1,2</sup>, 王永春<sup>3</sup>, 王阿红<sup>3※</sup>, 周济<sup>1,4※</sup>

<sup>1</sup> 南京农业大学前沿交叉研究院/作物表型组学交叉研究中心，江苏 南京 210095

<sup>2</sup> 南京农业大学工学院，江苏 南京 210031

<sup>3</sup> 中国科学院分子植物科学卓越创新中心/中国科学院国家基因研究中心，上海 200233

<sup>4</sup> 英国国立农业植物研究所/英国剑桥作物研究中心，剑桥 CB3 0LE，英国

## 概述
在本次发布中，我们上传了最新版本的水稻穗粒相关性状智能检测算法，算法结合了穗粒表型、图像处理和深度学习技术，可以在无需脱粒的前提下通过稻穗图像考察每穗粒数和多种穗粒相关性状，适用于高清照相机、智能手机或扫描仪等拍摄设备在室内外多种场景下采集的图像。结果表明，本研究构建的算法应用范围广、使用便捷且成本低，性状分析结果具有生物学意义。因此适用于对精确度和泛化性要求较高的穗粒性状快速鉴定及分型工作，为智能化穗粒性状解析提供了新思路和新方法。


## 安装Python, Anaconda和相关依赖库
如果您想要从代码运行本算法，则需要将Python和相关依赖库部署到您所使用的操作系统中。

1. 安装Python:

  •	 若您初次接触Python语言，请参阅以下指南：
 https://wiki.python.org/moin/BeginnersGuideChinese
 
  •	 Windows系统用户，请从以下链接下载Python 3 发行版：
 https://www.python.org/downloads/windows/
 
  •	 本算法仅支持Python 3
 
2. 安装Anaconda Python 发行版：

  •	 参阅此安装指南：https://docs.continuum.io/anaconda/install/
 
  •	 Windows用户可参阅此详细指南：https://docs.continuum.io/anaconda/install/windows 
 
  •	 推荐安装最新版的Anaconda
 
3. 相关依赖库：

 • 本算法使用了一些第三方的开源库，在运行前需要将它们添加至您的conda环境中，包括但不限于：
 
    numpy == 1.20.3
    pandas == 1.3.3
    pytorch == 1.9.1
    scikit-image == 0.18.1
    scipy == 1.7.1
  
## 致谢

感谢中国科学院国家基因研究中心为本研究提供了水稻材料、相关图片和宝贵意见。该工作同时得到了中央高校基本科研专项资金（JCQY201902）、国家自然科学青年基金（项目编号：32001516）和中国科学院先导专项（项目编号：XDA24020205）的资助。


## 知识产权声明
基于图像的水稻穗粒相关性状智能检测算法由周济实验室（中）研发，且相关的图像采集与数据分析流程已与中国科学院国家基因研究中心共同向国家知识产权局提交专利保护申请（整穗图像处理方法和装置，申请号202110614869.5）。算法的任何副本可自由供科研使用，相关的一切所有权和知识产权均归南京农业大学周济实验室拥有，不得用于任何商业途径，违者属于侵权行为，并自行承担有此引起的不利后果。科研工作者如需修改本算法，可联系周济实验室（中）对算法功能、性能等进行必要的修改，但不得去除周济实验室（中）或南京农业大学的版本标示。 　　

<b>凡有上述侵权行为的个人、法人或其它组织，必须立即停止侵权、并对侵权造成的一切不良后果承担全部责任。周济实验室（中）将依据《中华人民共和国专利法》、《著作权法》等相关法律、法规追究其经济责任和法律责任。</b>

有意合作者可通过Email: Ji.Zhou@njau.edu.cn或wd@njau.edu.cn 与实验室取得联系。如选择使用本算法，即接受本协议所有条款。

 
