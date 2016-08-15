# csr
&#160; &#160; &#160; &#160;规则方法联合机器学习方法  
<br>
##简介
&#160; &#160; &#160; &#160;一种联合规则和机器学习进行情绪分类的方法，该部分首先采取规则方法获得句子级的结果，接着将每一条微博表示为句子级情绪的序列，然后从训练集中挖掘类别序列规则（Class Sequential Rule, CSR）,从挖掘出的规则中提取新的特征，最后使用SVM获得微博级别的分类结果。

##文件说明

* prepare_for_csr/get_csr.py<br>
  把训练集和测试集都处理成序列模式，并且得到训练集中的所有子序列。

* get_csr/extract_csr.py<br>
  csr挖掘规则从子序列中挖掘出csr。

* evaluate/performance.py<br>
  performance库,多种常用的评估指标如acc、precision、recall等。

* evaluate/process.py<br>
  计算各种指标。




