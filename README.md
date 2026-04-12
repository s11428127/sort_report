# 排序報告
學號: 11428127 
姓名:  
模擬頁面: https://s11428127.github.io/sort_report/index.html
## 氣泡排序法
基本原理：像水中的氣泡一樣，較大的數值會逐漸「浮」到陣列的頂端。

操作方式：從陣列的第一個元素開始，兩兩比較相鄰的元素。如果前一個元素大於後一個元素，則將兩者交換。每一輪比較結束後，該輪最大的元素會被推到未排序部分的最後面。重複此過程直到沒有元素需要交換為止。

<img width="313" height="359" alt="image" src="https://github.com/user-attachments/assets/c9e822ad-0d32-4c8b-991b-5c96e8b59c1f" />

## 選擇排序法
基本原理：每次從尚未排序的數列中，尋找最小值，並將其與未排序部分的第一個元素交換。

操作方式：將陣列分為「已排序」與「未排序」兩部分。初始狀態下已排序部分為空。演算法掃描未排序部分，找出最小值，將其加入已排序部分的末端（即與未排序部分的開頭交換）。反覆執行直到所有元素皆排序完畢。

<img width="305" height="389" alt="image" src="https://github.com/user-attachments/assets/fd8c9d37-ca37-4cff-b971-5d7f61f2954f" />

## 插入排序法
基本原理：類似打撲克牌時整理手牌的方式，將新拿到的牌插入已排好序的手牌中的正確位置。

操作方式：將陣列的第一個元素視為已排序。接著從第二個元素開始，逐一與前面已排序的元素由後往前比較，若前面的元素較大，則將前面的元素往後移，直到找到合適的位置將當前元素插入。

<img width="381" height="291" alt="image" src="https://github.com/user-attachments/assets/77cda216-f91f-4bd0-941f-224008caa681" />

## 合併排序法
基本原理：採用「分治法 (Divide and Conquer)」策略。

操作方式：將陣列不斷對半分割，直到每個子陣列只剩下一個元素（此時視為已排序）。接著將相鄰的子陣列兩兩合併，在合併的過程中進行排序，最終合併回一個完整的已排序陣列。

<img width="411" height="302" alt="image" src="https://github.com/user-attachments/assets/34540449-0d51-43e6-96f2-a3362cd8582c" />

## 堆積排序法
基本原理：利用「二元樹」中的「最大堆積 (Max-Heap)」資料結構來進行排序。

操作方式：首先將未排序的陣列建構成一個 Max-Heap（父節點的值永遠大於等於子節點）。接著將堆積的根節點（最大值）與陣列最後一個元素交換，並將堆積的大小減一。然後對新的根節點重新進行 Heapify 調整，使其恢復 Max-Heap 特性。重複此動作直到堆積大小為 1。

<img width="528" height="283" alt="image" src="https://github.com/user-attachments/assets/cf56d799-ac2c-41f5-a1e4-54edf844e4ba" />










