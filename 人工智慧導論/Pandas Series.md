## Series基本

### 

```
安裝Pandas
import pandas as pd
```
建立Series數值
```
obj = pd.Series([49, 67, -52, 35])
obj
------
0    49
1    67
2   -52
3    35
dtype: int64
```
#### 顯示數值
```
obj.values
--------
array([ 49,  67, -52,  35])
```
#### 也可自己設定index的標籤，再藉由搜尋標籤而取得對應數值
```
obj2 = pd.Series([40, 70, -51, 32], index=['d', 'b', 'a', 'c'])
obj2
------------------
d    40
b    70
a   -51
c    32
dtype: int64
```
```
obj2.index
-----
Index(['d', 'b', 'a', 'c'], dtype='object')
```



