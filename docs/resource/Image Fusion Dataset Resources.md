# 圖像融合數據集資源整理

## 1. 基礎融合任務數據集

### 可見光-紅外融合

- **LLVIP Dataset**
  - 規模: 12025對訓練圖像, 70對測試圖像
  - 特點: 低光照條件下的配對數據
  
- **TNO Dataset**
  - 特點: 軍事場景為主
  - 包含: 不同天氣與光照條件

### 多曝光融合

- **SCIE Dataset**
  - 規模: 589對圖像
  - 特點: 包含多種場景與曝光條件

- **MEFB Dataset**
  - 規模: 100對測試圖像
  - 特點: 專注於評估用途

### 多焦點融合

- **RealMFF Dataset**
  - 特點: 真實場景拍攝
  - 包含: 自然場景與人工物體

- **MFI-WHU Dataset**
  - 特點: 高質量對準
  - 包含: 複雜場景數據

## 2. 擴展任務數據集

### 多光譜融合

- **Worldview-3 Dataset**
  - 分辨率: 0.31m全色, 1.24m多光譜
  - 波段: 8個多光譜波段

- **GaoFen-2 Dataset**
  - 分辨率: 0.8m全色, 3.2m多光譜
  - 特點: 中國自主衛星數據

### 全色圖像銳化

- **SpaceNet Dataset**
  - 規模: 大規模衛星影像
  - 地區: 多個城市區域

- **QuickBird Dataset**
  - 分辨率: 0.6m全色, 2.4m多光譜
  - 覆蓋: 全球多個區域

### 醫學圖像融合

- **BraTS Dataset**
  - 模態: T1, T2, FLAIR, T1CE
  - 病例: 腦腫瘤分割標註

- **ISLES Dataset**
  - 特點: 缺血性卒中病灶
  - 包含: 多模態MRI序列

### 遙感圖像融合

- **SEN12MS Dataset**
  - 數據源: Sentinel-1, 2和MODIS
  - 規模: 180,662個圖像塊

- **IEEE GRSS Data Fusion Contest**
  - 特點: 年度更新
  - 包含: 多種遙感任務

## 3. 特殊應用數據集

### 多時相融合

- **SZTAKI AirChange**
  - 特點: 航空影像變化檢測
  - 時間跨度: 多年

### 深度圖像融合

- **NYU Depth V2**
  - 規模: 464個場景
  - 數據: RGB-D配對

### 多相機融合

- **Oxford RobotCar**
  - 數據類型: 多傳感器
  - 時長: 1000多小時

### HDR成像

- **HDR-Eye**
  - 特點: 人眼感知導向
  - 場景: 多種室內外環境

## 4. 數據獲取注意事項

1. 數據下載需要註冊或申請
2. 部分數據集有使用限制
3. 需要考慮存儲空間
4. 預處理需求不同

## 5. 建議使用順序

1. 先用基礎任務數據集驗證
2. 再用擴展任務數據集測試
3. 最後考慮特殊應用數據集
