# A Fast Sync to Ethereum 以太坊快速同步

Bring you to the current state of Ethereum.


## 撰書目的

- 將開發者快速推到前線
- 提供翻譯標準

## 風格

### 適應高速變化的生態系

選擇短期較不易變動、已上線運作的內容撰寫。太新的內容以連結方式呈現。故名快速同步（Fast Sync），讀者仍要自己去讀最新的內容達成全同步（Full Sync）

### 針對不同角色設計

本書的目標讀者為下列四種，每章會粗略分為四個區段，針對不同角色解說

- 五歲兒童：針對一般人想了解一些名詞、在餐桌上解釋給親友設計。
- 開發者：會講解一個客戶端的程式碼，說明實作細節，讓開發者好上手。
- 研究者：指出目前的研究方向，讓有志於研究者上手。
- 資安研究：針對攻擊案例簡介、分析。

### 建立理解

- 新的生字在書中應該被定義。例如：
    - 如果書中提到「礦工」，讀者應該要能找到相應的定義。
- 特殊的動詞應該被解釋，例如：
    - 「上鏈」：讀者看完這本書應該要能理解，這意涵資料被記載在每個節點上。
    - 「發交易」：讀者看完這本書應該要能理解交易是由 p2p 網路廣播出去。

### 開放給社群貢獻

沒有人會把這本書寫完

## 預計章節架構

- 以太坊生態系
- 以太坊 1.0
    - client
    - p2p
    - evm
    - dapp
- 以太坊 2.0
    - casper
    - sharding
    - plasma
- 先備知識
    - 賽局理論
    - 密碼學
    - 分散式系統
- 詞彙表


## 協作方式

在 [Github](https://github.com/EtherTW/a-fast-sync-to-ethereum) 協作，以 Gitbook 發行。協作者以 Pull Request 提交更改。會有同儕審查。

```bash
$ git clone git@github.com:EtherTW/a-fast-sync-to-ethereum.git
$ make install
$ make serve
```


## 授權

CC0