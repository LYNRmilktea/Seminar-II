### 日期：2026/05/05

### 講者：Chih-Lin Hu（胡誌麟）教授  

### 題目：群眾感測技術與應用案例

#### 學號: 11463111
#### 姓名: 劉柏毅

# 心得

這次演講「群眾感測技術與應用案例」，主要介紹Mobile Crowd Sensing(MCS)以及在智慧城市和交通風險預測，使用者獎勵的應用，這次演講，我了解到群眾感測並不是單純收集資料而已，是利用大量使用者的手機、穿戴式裝置、車載設備，協助系統取得環境、交通、位置等資料，再將資料進行分析與預測。

在應用中，MCS可以結合交通系統與行動使用者所提供的資料，例如車流量、天氣、道路事故、位置等資訊，這些資料有空間與時間上的關聯，如同一區域附近的交通狀況可能互相影響，不同時段也會出現不同的交通模式，要進行交通風險預測，不能只看單一資料，而是需要同時考慮空間與時間的變化。

演講中提到的CarView系統，利用深度學習方法，結合CNN與LSTM來分析交通風險，CNN 適合處理空間上的特徵，例如不同區域之間的交通分布，LSTM 能處理時間序列資料，最後系統把交通風險以網格化的方式呈現，讓不同區域的風險程度可以被視覺化，這對駕駛安全和城市交通管理都有幫助，演講時特別講到在路徑上可以選擇比較安全的路，感覺也是蠻有想法的，畢竟在台灣的道路上三寶真的很多。

這次演講也讓我理解到MCS系統面臨不少問題，因為資料是由使用者提供，所以系統必須考慮資料可靠性、完整性，以及是否有惡意使用者提供錯誤資料來獲取獎勵，使用者在參與感測任務時，也會消耗手機電量、運算資源、網路頻寬，甚至可能產生隱私風險所以如果沒有合適的獎勵機制，使用者可能不願意長期參與。

在獎勵機制的部分，PPT中介紹了 Incentive-G 的設計，這個方法結合了資料品質分析、使用者信譽評估、投票驗證，以及Stackelberg game模型，系統不只是單純給使用者金錢，而是會根據資料品質、過去行為、其他使用者的投票結果等因素，來計算使用者的貢獻與獎勵，這樣的設計可以鼓勵使用者提供更可靠的資料，也能降低惡意使用者對系統造成的影響。

我覺得這場演講最重要的觀念是群眾感測系統的價值是在於如何從大量、複雜且可能不完整的資料中，建立可信任的分析與決策機制，尤其在交通風險預測這類應用中，如果資料品質不好，模型再複雜也可能得到錯誤結果所以，資料品質、使用者信譽、獎勵機制與AI分析方法其實是互相配合的，整體來說，這次演講讓我對MCS在智慧城市中的應用有完整的認識，過去我可能只會把交通預測想成是單純的AI模型問題又或是單純的演算法，但這次演講讓我知道，實際系統還要考慮資料來源、使用者行為、隱私風險、獎勵公平性與惡意資料防範等問題，這些都是讓一個智慧城市系統能夠真正落地的重要因素，最近也看到有些國家的紅綠燈是智能判別的，感覺這個系統也有機會運用在這上面似乎也挺有趣。

# Keywords

- Mobile Crowd Sensing
- MCS
- Smart City
- Traffic Risk Prediction
- Spatio-temporal Data
- Urban Sensing Data
- Deep Learning
- Convolutional Neural Network
- CNN
- Long Short-Term Memory
- LSTM
- Data Quality
- Data Reliability
- User Reputation
- Incentive Mechanism
- Reward Mechanism
- Monetary Reward
- Reputation Credit
- Voting Validation
- Stackelberg Game
- Nash Equilibrium
- Game Theory
- Service Provider
- Mobile Users
- CarView
- Incentive-G

# 參考文獻

1. https://orbilu.uni.lu/bitstream/10993/39438/1/comst-preprint.pdf
2. https://tns.thss.tsinghua.edu.cn/~yangzheng/papers/Zhang-Incentives-COMST2016.pdf
3. https://www.computer.org/csdl/journal/sc/2023/03/09857647/1FSY443CeGs
4. https://shameek.cs.wmich.edu/tmc_19.pdf
5. https://ieeexplore.ieee.org/document/8577032
