## data_clean 

```Python
#數據加載成dataframe
df = pd.read_csv('path')
#重設cloumns name
xx.columns([''])
#新增欄位
df['new_column'] = df['xx'] + 1
#刪除欄位
df.drop[columns=['']]
#把NaN一整個row刪掉
df.dropna()
#刪掉NaN所在的cloumn
df.drop(axis = 1)
#查詢欄位
#裡面要填idex
df.iloc[[]]
#裡面填value
df.loc['']
#以下是指column
axis = 1
#預設為row
axis = 0
#資料合併增加新的col預設為增加新的row
pd.concat([x, xx.rename()], axis = 1)
#資料排序遞減預設為遞增
df.sort_values(x, ascending = False)

```

## 常用語法
```Python
#印出前5筆資料
df.head()
#return bool
data.isnull()
#印出中位數,平均數,標準差...各種統計數據
df.describe()
#印出data的type
df.dtypes
#計算整個col有幾個..
df['col_name'].value_counts()
```
## data_visualization
```Python
#折線圖
plt.plot(x, y)
#長條圖
plt.bar(x, y)#x是數字
#也可以這樣xx是cloumn name
xx.plot(kind = 'bar')
#直方圖
plt.hist(x, y)#x是有組距
#圓餅圖
plt.pie(x)
#箱型圖
xx.boxplot(column='x')
sns.boxplot(x='', y='', data=x)
#畫出曲線分布
sns.distplot(xx)
#畫出散點圖
sns.reglot(x='xx', y='xx',data=xx, scatter=True)
df.plot.scatter(title='x', x='', y='')
#畫出散點圖矩陣
sns.pairplot(df)
#畫熱力圖
sns.heatmap('x', 'x')
#設定圖的x,y標題,title
plt.xlabel('xx')
plt.ylabel('xx')
plt.title('xx')
#畫出特定欄位的圖
df = xx[['x', 'x', 'x']
df.plot()
#設定x座標字體傾斜角度
plt.xticks(rotation=幾度)
#用sklearn把data標準化參數0,1可修改
scaler = MinMaxScaler(feature_range=(0, 1)).fit(df) 
df_scaled = scaler.transform(df)
```

## Math and Statistics
```Python
#創造np.array
a = np.array([[2, 4, 6], [1, 3, 5], [10, 20, 30]])
b = np.array([[0, 1, 2], [3, 4, 5], [6, 7, 8]])
#對應位置相乘
a*b
#內積
np.dot(a, b)
#把column x 中資料分組並算個數
x=df.x
x.value.counts()
#變量之間有線性關係使用皮爾森
#計算皮爾森相關係數
#1正相關, 0無線性相關,-1負相關
df.corr()
#沒有線性關係用斯皮爾曼等級相關係或卡方檢定
#計算斯皮爾曼等級相關係數
#r 是相關係數 
r, p_value = spearmanr('x', 'x')
#卡方檢定 p_value>0.05變量相互獨立
table = pd.crosstab('x','x')
chi2, p, dor, expected = chi_contingency(table)
#標準化數據 
form sklearn preprocessing
from sklearn.preprocessing import scale
std_x = scale(x)

```

## ML Dimension Reduction(降維)
```Python
???????
#降維PCA
import sklearn
from sklearn.decomposition import PCA
pca = PCA()
xx_pca = pca.fit.transform(x)
pca.explainde_variance_ratio_
```
## ML 異常值
```Python

```