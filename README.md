# ML_100Day
## 機器學習概論
##### 從概念上理解機器學習的目的與限制，並導覽機器學習流程
1. [資料介紹與評估資料](https://github.com/LinMeiChi/ML_100Day/blob/main/homework/Day_001_HW.ipynb)                           
挑戰是什麼?動手分析前請三思                                                                                                     
2. [機器學習概論](https://github.com/LinMeiChi/ML_100Day/blob/main/homework/Day_002_HW.ipynb)                                 
機器學習、深度學習與人工智慧差別是甚麼? 機器學習又有甚麼主題應用?
3. [機器學習 - 流程與步驟](https://github.com/LinMeiChi/ML_100Day/blob/main/homework/Day_003_HW.ipynb)                         
資料前處理 > 訓練/測試集切分 >選定目標與評估基準 > 建立模型 > 調整參數。熟悉整個 ML 的流程
4. [EDA/讀取資料與分析流程](https://github.com/LinMeiChi/ML_100Day/blob/main/homework/Day_004_HW.ipynb)                       
如何讀取資料以及萃取出想要了解的信息

## 資料清理數據前處理
##### 以滾動方式進行資料清理與探索性分析
5. [如何新建一個 dataframe? 如何讀取其他資料? (非 csv 的資料)](https://github.com/LinMeiChi/ML_100Day/blob/main/homework/Day_005-1_HW.ipynb)                                              
從頭建立一個 dataframe、如何讀取不同形式的資料 (如圖檔、純文字檔、json 等)
6. [EDA：欄位的資料類型介紹及處理](https://github.com/LinMeiChi/ML_100Day/blob/main/homework/Day_006_HW.ipynb)                 
了解資料在 pandas 中可以表示的類型
7. [特徵類型](https://github.com/LinMeiChi/ML_100Day/blob/main/homework/Day_007_HW.ipynb)                                     
特徵工程依照特徵類型，做法不同，大致可分為數值/類別/時間型三類特徵
8. [EDA資料分佈](https://github.com/LinMeiChi/ML_100Day/blob/main/homework/Day_008_HW.ipynb)                                 
用統計方式描述資料
9. [EDA: Outlier 及處理](https://github.com/LinMeiChi/ML_100Day/blob/main/homework/Day_009_HW.ipynb)                         
偵測與處理例外數值點：1. 透過常用的偵測方法找到例外 2. 判斷例外是否正常 (推測可能的發生原因)
10. [數值型特徵 - 去除離群值](https://github.com/LinMeiChi/ML_100Day/blob/main/homework/Day_010_HW.ipynb)                     
數值型特徵若出現少量的離群值，則需要去除以保持其餘數據不被影響
11. [常用的數值取代：中位數與分位數連續數值標準化](https://github.com/LinMeiChi/ML_100Day/blob/main/homework/Day_011_HW.ipynb)   
偵測與處理例外數值 (缺值或例外取代、數據標準化)
12. [數值型特徵-補缺失值與標準化](https://github.com/LinMeiChi/ML_100Day/blob/main/homework/Day_012_HW.ipynb)                   
數值型特徵首先必須填補缺值與標準化，在此複習並展示對預測結果的差異
13. [DataFrame operationData frame merge/常用的 DataFrame 操作](https://github.com/LinMeiChi/ML_100Day/blob/main/homework/Day_013_HW.ipynb)  
常見的資料操作方法、資料表串接
14. [程式實作 EDA: correlation/相關係數簡介](https://github.com/LinMeiChi/ML_100Day/blob/main/homework/Day_014_HW.ipynb)       
了解相關係數、利用相關係數直觀地理解對欄位與預測目標之間的關係
15. [EDA from Correlation](https://github.com/LinMeiChi/ML_100Day/blob/main/homework/Day_015_HW.ipynb)                       
深入了解資料，從 correlation 的結果下手
16. [EDA: 不同數值範圍間的特徵如何檢視/繪圖與樣式Kernel Density Estimation (KDE)](https://github.com/LinMeiChi/ML_100Day/blob/main/homework/Day_016_HW.ipynb)                       
如何調整視覺化方式檢視數值範圍、美圖修修 - 轉換繪圖樣式
17. [EDA: 把連續型變數離散化](https://github.com/LinMeiChi/ML_100Day/blob/main/homework/Day_017_HW.ipynb)                     
簡化連續性變數
18. [程式實作 把連續型變數離散化](https://github.com/LinMeiChi/ML_100Day/blob/main/homework/Day_018_HW.ipynb)                   
深入了解資料，從簡化後的離散變數下手
19. [Subplots](https://github.com/LinMeiChi/ML_100Day/blob/main/homework/Day_019_HW.ipynb)                                   
探索性資料分析 - 資料視覺化 - 多圖檢視 1. 將數據分組一次呈現 2. 把同一組資料相關的數據一次攤在面前
20. [Heatmap & Grid-plot](https://github.com/LinMeiChi/ML_100Day/blob/main/homework/Day_020_HW.ipynb)                         
探索性資料分析 - 資料視覺化 - 熱像圖 / 格狀圖 1. 熱圖：以直觀的方式檢視變數間的相關性 2. 格圖：繪製變數間的散佈圖及分布
21. [模型初體驗 Logistic Regression](https://github.com/LinMeiChi/ML_100Day/blob/main/homework/Day_021_HW.ipynb)             
在我們開始使用任何複雜的模型之前，有一個最簡單的模型當作 baseline 是一個好習慣

## 資料科學特徵工程技術
##### 使用統計或領域知識，以各種組合調整方式，生成新特徵以提升模型預測力。
22. [特徵工程簡介](https://github.com/LinMeiChi/ML_100Day/blob/main/homework/Day_022_HW.ipynb)                                
介紹機器學習完整步驟中，特徵工程的位置以及流程架構
23. [數值型特徵 - 去除偏態](https://github.com/LinMeiChi/ML_100Day/blob/main/homework/Day_023_HW.ipynb)                       
數值型特徵若分布明顯偏一邊，則需去除偏態以消除預測的偏差
