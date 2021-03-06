# 📌 链接预测
🔗 [Predicting Disease Related microRNA Based on Similarity and Topology](https://www.mdpi.com/2073-4409/8/11/1405 "Cells")  
🔗 [PyTorch实现的表示学习工具包——**CogDL**: An Extensive Research Platform for Deep Learning on Graphs](https://github.com/THUDM/cogdl/ "GitHub链接，点击访问")  
>> 2019年12月17日，集成图网络模型实现、基准测试，清华推出`图表示学习`工具包

# IGAL Learning Summary
ing 
## miRNA-disease association summary
> - 2010年, Jiang等人 
> - 2011年，Xu等人 
> - 2012年，Chen等人，RWRMDA
> - 2013年，Xuan等人，HDMP
> - 2014年，Chen等人，RLSMDA
> - 2015年，Xuan等人，MIDP
> - 2015年，Chen等人，RBMMMDA
> - 2016年，Chen等人，WBSMDA
> - 2016年，Chen等人，HGIMDA
> - 2016年，Pasquier等人，MiRAI
> - 2017年，Fu等人，DeepMDA
> - 2017年，Chen等人，RKNNMDA
> - 2018年，Chen等人，MDHGI
> - 2018年，Chen等人，IMCMDA
> - 2019年，Chen等人，EDTMDA
> - the other  
**Happy New Year!**

## Network_Embedding :dart:
#### For generating MetaPAths with M-D-G-D-M patterns. This file could be ran on windows with cmd or powershell.
> - where M means miRNA, D means Disease, G means Gene.
#### 网络结构图绘制
> - [NN SVG](http://alexlenail.me/NN-SVG/index.html)
#### Link2Vec
> - Start Now !
#### Deep Forest
> - 
#### Tips
> - 网络节点编码时，应当处理为不同的id。比如: disease节点从0开始编码，miRNA也从0开始编码。这样做可能不够合理，因为所利用的嵌入算法是对网络节点id进行随机游走，从而形成语料库。若出现不同类型的节点拥有相同的id，可能会造成训练词向量时的误差。
