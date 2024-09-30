```mermaid
gantt
    title A Gantt Diagram

    section Section
    研擬計畫           :a1, 2024-01-01, 1d
    任務分配     :a2,after a1  , 4d
    取得硬體      :a3,after a1  , 17d
    程式開發      : a4,after a2,70d
    安裝硬體      : a5,after a3,10d
    程式測試      : a6,after a4,30d
    撰寫使用手冊      : a7,after a5,25d
    轉換檔案      : a8,after a5,20d
    系統測試      : a9,after a6,25d
    使用者訓練      : a10,after a7 a8,20d
    使用者測試      : after a9 a10,25d
```
![petg](https://github.com/Kayu10/homework/blob/main/graphviz%20(1).png)
```mermaid
graph TD
    A[研擬計畫] --> B[任務分配]
    A--> C[取得硬體]
    B --> D[程式開發]
    C --> E[安裝硬體]
    D --> F[程式測試]
    E --> G[撰寫使用手冊]
    E --> H[轉換檔案]
    F --> I[系統測試]
    H --> J[使用者訓練]
    I --> K[使用者測試]
    G --> J
    J --> K


```
