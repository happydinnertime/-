# 資料視覺化
```
資料視覺化是資料分析中一個重要的部分。
它也可能是探索資料的一部分，比如，幫助我們找到離群點或需要進行變換的資料，或説明我們思考選擇哪種模型更合適。

此單元用Jupyter notebook進行可互動式的繪圖
Jupyter notebook:
(https://nbviewer.jupyter.org/github/LearnXu/pydata-notebook/blob/master/Chapter-09/9.1%20A%20Brief%20matplotlib%20API%20Primer%EF%BC%88%E4%B8%80%E4%B8%AA%E7%AE%80%E5%8D%95%E7%9A%84matplotlib%20API%E5%85%A5%E9%97%A8%EF%BC%89.ipynb)
----------------------------------------------------------------------------
執行下面的語句，就可直接在Notebook裡繪圖:

%matplotlib notebook
```
```
%matplotlib inline
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
data = np.arange(10)
data
plt.plot(data)
```
