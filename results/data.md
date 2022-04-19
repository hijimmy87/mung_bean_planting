# 目錄
- [圖表](#圖表)
- [數據統計](#數據統計)
- [單因子變異數分析](#單因子變異數分析)
- [各組間檢定結果](#各組間檢定結果)
  - [純水與 0.1% 食鹽水](#純水與-01-食鹽水)
  - [純水與 0.3% 食鹽水](#純水與-03-食鹽水)
  - [純水與 0.5% 食鹽水](#純水與-05-食鹽水)
  - [純水與 1.0% 食鹽水](#純水與-10-食鹽水)
  - [0.1% 食鹽水與 0.3% 食鹽水](#01-食鹽水與-03-食鹽水)
  - [0.1% 食鹽水與 0.5% 食鹽水](#01-食鹽水與-05-食鹽水)
  - [0.1% 食鹽水與 1.0% 食鹽水](#01-食鹽水與-10-食鹽水)
  - [0.3% 食鹽水與 0.5% 食鹽水](#03-食鹽水與-05-食鹽水)
  - [0.3% 食鹽水與 1.0% 食鹽水](#03-食鹽水與-10-食鹽水)
  - [0.5% 食鹽水與 1.0% 食鹽水](#05-食鹽水與-10-食鹽水)


# 圖表
![line chart](./line_chart.jpg)

# 數據統計
測量項目為綠豆的大小，單位為面積。
|　　　　　　|純水  |0.1% |0.3% |0.5% |1.0% |
|----------|-----|-----|-----|-----|-----|
|樣本數　　　|34   |34   |34   |34   |34   |
|平均　　　　|1.686|1.780|1.158|1.154|0.614|
|標準差　　　|0.556|0.504|0.199|0.133|0.075|
|最小值　　　|0.944|0.898|0.757|0.921|0.474|
|第一四分位數|1.194|1.310|0.992|1.048|0.544|
|中位數　　　|1.647|1.846|1.153|1.184|0.626|
|第三四分位數|2.158|2.314|1.259|1.265|0.662|
|最大值　　　|2.757|2.599|1.662|1.383|0.742|

# 觀測紀錄
|日期|氣溫(℃)|備註|
|---|:-----:|---|
|4/1 19:07|21.0|開始種植|
|4/2 00:29|21.5||
|4/3 00:26|21.0||
|4/4 03:18|20.5||
|4/5 00:09|20.0||
|4/6 00:12|21.0||

---

# 單因子變異數分析
|變源|SS|自由度|MS|F|P-值|臨界值|
|---|-|-|-|-|-|-|
|組間|30.245|4|7.561|58.614|1.04×10<sup>-30</sup>|2.426
|組內|21.285|165|0.129|||
||||||
|總和|51.529|169||||


---

# 各組間檢定結果

## 純水與 0.1% 食鹽水
[回頁首](#目錄)
#### F 檢定
|   |純水|0.1%|
|---|---|----|
|平均數|1.686|1.780|
|變異數|0.318|0.262|
|觀察值個數|34|34|
|自由度|33|33|
|F|1.214||
|P(F<=f) 單尾|0.291||
|臨界值：單尾|1.788||

#### 同質性 t 檢定
|   |純水|0.1%|
|---|---|----|
|平均數|1.686|1.780|
|變異數|0.318|0.262|
|觀察值個數|34|34|
|Pooled 變異數|0.290||
|假設的均數差|0||
|自由度|66||
|t 統計|-0.717||
|P(T<=t) 單尾|0.238||
|臨界值：單尾|1.668||
|P(T<=t) 雙尾|0.476||
|臨界值：雙尾|1.997||

---

## 純水與 0.3% 食鹽水
[回頁首](#目錄)
#### F 檢定
|   |純水|0.3%|
|---|---|----|
|平均數|1.686|1.158|
|變異數|0.318|4.08×10<sup>-2</sup>|
|觀察值個數|34|34|
|自由度|33|33|
|F|7.793||
|P(F<=f) 單尾|2.71×10<sup>-8</sup>||
|臨界值：單尾|1.788||

#### 異質性 t 檢定
|   |純水|0.3%|
|---|---|----|
|平均數|1.686|1.158|
|變異數|0.318|4.08×10<sup>-2</sup>|
|觀察值個數|34|34|
|假設的均數差|0||
|自由度|41||
|t 統計|5.137||
|P(T<=t) 單尾|3.61×10<sup>-6</sup>||
|臨界值：單尾|1.683||
|P(T<=t) 雙尾|7.21×10<sup>-6</sup>||
|臨界值：雙尾|2.020||

---

## 純水與 0.5% 食鹽水
[回頁首](#目錄)
#### F 檢定
|   |純水|0.5%|
|---|---|----|
|平均數|1.686|1.154|
|變異數|0.318|1.82×10<sup>-2</sup>|
|觀察值個數|34|34|
|自由度|33|33|
|F|17.492||
|P(F<=f) 單尾|3.28×10<sup>-13</sup>||
|臨界值：單尾|1.788||

#### 異質性 t 檢定
|   |純水|0.5%|
|---|---|----|
|平均數|1.686|1.154|
|變異數|0.318|1.82×10<sup>-2</sup>|
|觀察值個數|34|34|
|假設的均數差|0||
|自由度|37||
|t 統計|5.351||
|P(T<=t) 單尾|2.38×10<sup>-6</sup>||
|臨界值：單尾|1.687||
|P(T<=t) 雙尾|4.75×10<sup>-6</sup>||
|臨界值：雙尾|2.026||

---

## 純水與 1.0% 食鹽水
[回頁首](#目錄)
#### F 檢定
|   |純水|1.0%|
|---|---|----|
|平均數|1.686|0.614|
|變異數|0.318|5.56×10<sup>-3</sup>|
|觀察值個數|34|34|
|自由度|33|33|
|F|54.276||
|P(F<=f) 單尾|8.03×10<sup>-21</sup>||
|臨界值：單尾|1.788||

#### 異質性 t 檢定
|   |純水|1.0%|
|---|---|----|
|平均數|1.686|0.614|
|變異數|0.318|5.56×10<sup>-3</sup>|
|觀察值個數|34|34|
|假設的均數差|0||
|自由度|34||
|t 統計|10.989||
|P(T<=t) 單尾|4.94×10<sup>-13</sup>||
|臨界值：單尾|1.691||
|P(T<=t) 雙尾|9.87×10<sup>-13</sup>||
|臨界值：雙尾|2.032||

---

## 0.1% 食鹽水與 0.3% 食鹽水
[回頁首](#目錄)
#### F 檢定
|   |0.1%|0.3%|
|---|----|----|
|平均數|1.780|1.158|
|變異數|0.262|4.08×10<sup>-2</sup>|
|觀察值個數|34|34|
|自由度|33|33|
|F|6.421||
|P(F<=f) 單尾|3.15×10<sup>-7</sup>||
|臨界值：單尾|1.788||

#### 異質性 t 檢定
|   |0.1%|0.3%|
|---|----|----|
|平均數|1.780|1.158|
|變異數|0.262|4.08×10<sup>-2</sup>|
|觀察值個數|34|34|
假設的均數差|0||
|自由度|43||
|t 統計|6.584||
|P(T<=t) 單尾|2.59×10<sup>-8</sup>||
|臨界值：單尾|1.681||
|P(T<=t) 雙尾|5.17×10<sup>-8</sup>||
|臨界值：雙尾|2.017||

---

## 0.1% 食鹽水與 0.5% 食鹽水
[回頁首](#目錄)
#### F 檢定
|   |01.%|0.5%|
|---|----|----|
|平均數|1.780|1.154|
|變異數|0.262|1.82×10<sup>-2</sup>|
|觀察值個數|34|34|
|自由度|33|33|
|F|14.412||
|P(F<=f) 單尾|5.60×10<sup>-12</sup>||
|臨界值：單尾|1.788||

#### 異質性 t 檢定
|   |0.1%|0.5%|
|---|----|----|
|平均數|1.780|1.154|
|變異數|0.262|1.82×10<sup>-2</sup>|
|觀察值個數|34|34|
假設的均數差|0||
|自由度|38||
|t 統計|6.892||
|P(T<=t) 單尾|1.72×10<sup>-8</sup>||
|臨界值：單尾|1.686||
|P(T<=t) 雙尾|3.44×10<sup>-8</sup>||
|臨界值：雙尾|2.024||

---

## 0.1% 食鹽水與 1.0% 食鹽水
[回頁首](#目錄)
#### F 檢定
|   |0.1%|1.0%|
|---|----|----|
|平均數|1.780|0.614|
|變異數|0.262|5.56×10<sup>-3</sup>|
|觀察值個數|34|34|
|自由度|33|33|
|F|44.721||
|P(F<=f) 單尾|1.74×10<sup>-19</sup>||
|臨界值：單尾|1.788||

#### 異質性 t 檢定
|   |0.1%|1.0%|
|---|----|----|
|平均數|1.780|0.614|
|變異數|0.262|5.56×10<sup>-3</sup>|
|觀察值個數|34|34|
假設的均數差|0||
|自由度|34||
|t 統計|13.138||
|P(T<=t) 單尾|3.52×10<sup>-15</sup>||
|臨界值：單尾|1.691||
|P(T<=t) 雙尾|7.04×10<sup>-15</sup>||
|臨界值：雙尾|2.032||

---

## 0.3% 食鹽水與 0.5% 食鹽水
[回頁首](#目錄)
#### F 檢定
|   |0.3%|0.5%|
|---|----|----|
|平均數|1.158|1.154|
|變異數|4.08×10<sup>-2</sup>|1.82×10<sup>-2</sup>|
|觀察值個數|34|34|
|自由度|33|33|
|F|2.245||
|P(F<=f) 單尾|0.011||
|臨界值：單尾|1.788||

#### 異質性 t 檢定
|   |0.3%|0.5%|
|---|----|----|
|平均數|1.158|1.154|
|變異數|4.08×10<sup>-2</sup>|1.82×10<sup>-2</sup>|
|觀察值個數|34|34|
假設的均數差|0||
|自由度|58||
|t 統計|0.104||
|P(T<=t) 單尾|0.459||
|臨界值：單尾|1.672||
|P(T<=t) 雙尾|0.917||
|臨界值：雙尾|2.002||

## 0.3% 食鹽水與 1.0% 食鹽水
[回頁首](#目錄)
#### F 檢定
|   |0.3%|1.0%|
|---|----|----|
|平均數|1.158|0.614|
|變異數|4.08×10<sup>-2</sup>|5.56×10<sup>-3</sup>|
|觀察值個數|34|34|
|自由度|33|33|
|F|6.965||
|P(F<=f) 單尾|1.14×10<sup>-7</sup>||
|臨界值：單尾|1.788||

#### 異質性 t 檢定
|   |0.3%|1.0%|
|---|----|----|
|平均數|1.158|0.614|
|變異數|4.08×10<sup>-2</sup>|5.56×10<sup>-3</sup>|
|觀察值個數|34|34|
假設的均數差|0||
|自由度|42||
|t 統計|14.705||
|P(T<=t) 單尾|1.82×10<sup>-18</sup>||
|臨界值：單尾|1.682||
|P(T<=t) 雙尾|3.63×10<sup>-18</sup>||
|臨界值：雙尾|2.018||

---

## 0.5% 食鹽水與 1.0% 食鹽水
[回頁首](#目錄)
#### F 檢定
|   |0.5%|1.0%|
|---|----|----|
|平均數|1.154|0.614|
|變異數|1.82×10<sup>-2</sup>|5.56×10<sup>-3</sup>|
|觀察值個數|34|34|
|自由度|33|33|
|F|3.103||
|P(F<=f) 單尾|8.22×10<sup>-4</sup>||
|臨界值：單尾|1.788||

#### 異質性 t 檢定
|   |0.5%|1.0%|
|---|----|----|
|平均數|1.154|0.614|
|變異數|1.82×10<sup>-2</sup>|5.56×10<sup>-3</sup>|
|觀察值個數|34|34|
假設的均數差|0||
|自由度|52||
|t 統計|20.325||
|P(T<=t) 單尾|1.06×10<sup>-26</sup>||
|臨界值：單尾|1.675||
|P(T<=t) 雙尾|2.12×10<sup>-26</sup>||
|臨界值：雙尾|2.007||