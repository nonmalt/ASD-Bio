# Autistic Spectrum Disorder Bioinformatics Analysis
## Background
研究表明，肠道菌群会通过肠-脑轴等的机制影响人神经系统；基于健康人群与ASD患者的肠道菌群扩增子测序结果，我们期望通过识别肠道菌群中的差异物种来实现对于ASD的判别以及潜在干预靶点的确定。  
对此我们使用机器学习方法（Random Forest）来构建健康/ASD判别模型，并基于模型解释来确定其中的关键生物标志物；在此基础之上使用统计检验来确定物种在不同人群中的差异性。  
之后通过计算α-多样性，β-多样性来分析在菌群组成及结构上的两个群体之间的差异。  
  
## Dependences
Python 3: numpy, pandas, scikit-learn, scikit-bio, scipy, matplotlib

	pip install -r requirements.txt

## Target
1. 根据机器学习给出的生物标志物列表，采用统计学方法检验其中各物种的差异  
2. 利用给出的方法计算α-多样性指数及β-多样性距离  
3. 根据计算结果绘制α-多样性箱线图  
4. 计算两组别之间α-多样性是否存在差异  
5. 根据计算结果绘制β-多样性散点图  
