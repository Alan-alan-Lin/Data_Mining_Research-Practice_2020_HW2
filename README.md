# Data_Mining_Research-Practice_2020_HW2
HW2 - Cross Validation  
資料集 : Income Prediction  
目標 : 利用資料集其他欄位進行預測，預測目標是income (<=50K或>50K兩種)  
流程 :  
1.資料前處理  
2.使用Random Forest進行分類  
3.自行撰寫function進行k-fold cross-validation(不使用套件)並計算Accuracy  
  3-1. input(k, data)，將data切成k份，其中1份當測試集，剩餘k-1份當訓練集建立模型  
  3-2. 輪流將k份的每份資料都當 測試集，其餘當訓練集建立模型，因此會進行k次，k次都計算出Accuracy  
  3-3. 將k次的Accuracy平均即為output  
4.印出k=10時的Accuracy  
