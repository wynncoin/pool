# wynn-pool


### 發布說明(Comment)


* WYNN礦池工具，基於 UNOMP 參見 https://github.com/UNOMP/unified-node-open-mining-portal
* 依靠： redis , node.js(v0.10) , wynn wallet 
* 創世貼(正體): https://bitcointalk.org/index.php?topic=5128984
* 算法: sha256tx
* 說明：本算法爲執行三次sha256，並將首次與末次進行異或操作
* 聯系敬請電郵到 foundation@wynncoin.net
* 開發者：永利幣基金會
* 站點： https://www.wynncoin.net
* 應用說明： 
** 將 node_modules/merged-pooler/lib/transactions.js 第127行和 134行寫入許可伺服器的地址和通道資訊
** 將 pool_configs/wynn.json 中提示需要更換的資訊換成實際資訊
** 需要的node.js版本爲 0.10+



* stratum pool for WYNN is base UNOMP (https://github.com/UNOMP/unified-node-open-mining-portal)
* depends： redis , node.js(v0.10) , wynn wallet 
* ANN(English): https://bitcointalk.org/index.php?topic=5128975
* algo: sha256tx
* remark: mid = sha256(data); hash = sha256(sha256(mid)) XOR mid 
* author: WYNN foundation
* contact us : foundation@wynncoin.net
* website:  https://www.wynncoin.net
* Notice:
** edit node_modules/merged-pooler/lib/transactions.js write right information at line 127 and line 134
** edit pool_configs/wynn.json set right information
** depends node.js v0.10+





