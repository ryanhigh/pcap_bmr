# pcap_bmr
良性恶意流量抓取的特征选取与分类预测
## Sec.1
特征选择：
/pcap/离散点分布图.ipynb ：先尝试进行差异性分析
/pcap/特征选取.ipynb : 利用Mannwhitney U / K-S / Kruskal-Wallis H 检测选取差异性较大的特征
## Sec.2
分类预测：
/bmr : 利用了逻辑回归、随机森林、卷积神经网络CNN的方法，并利用三种测试进行准确率测试。
