# Part 4 分片 #

## 13. 分片 ##

13.1 分片簡介  
13.2 理解集群的組件  
13.3 快速建立一個簡單的集群  

## 14. 配置分片 ##

14.1 何時分片  
14.2 啟動服務器  
> 14.2.1 配置服務器  
> 14.2.2 mongos 進程  
> 14.2.3 將副本集轉換為分片  
> 14.2.4 增加集群容量  
> 14.2.5 數據分片  

14.3 MongoDB 如何追蹤集群數據  
> 14.3.1 塊範圍  
> 14.3.2 拆分塊  

14.4 均衡器  

## 15. 選擇片鍵 ##

15.1 檢查使用情況  
15.2 數據分發  
> 15.2.1 升序片鍵  
> 15.2.2 隨機分發的片鍵  
> 15.2.3 基於位置的片鍵  

15.3 片鍵策略  
> 15.3.1 散列片鍵  
> 15.3.2 GridFS 的散列片鍵  
> 15.3.3 流水策略  
> 15.3.4 多熱點  

15.4 片鍵規則和指導方針  
> 15.4.1 片鍵限制  
> 15.4.2 片鍵的勢  

15.5 控制數據分發  
> 15.5.1 對多個數據庫和集合使用一個集群  
> 15.5.2 手動分片  

## 16. 分片管理 ##

16.1 檢查集群狀態  
> 16.1.1 使用 sh.status 查看集群摘要訊息  
> 16.1.2 檢查配置信息  

16.2 查看網絡連接  
> 16.2.1 查看連接統計  
> 16.2.2 限制連接數量  

16.3 服務器管理  
> 16.3.1 添加服務器  
> 16.3.2 修改分片的服務器  
> 16.3.3 刪除分片  
> 16.3.4 修改配置服務器  

16.4 數據均衡  
> 16.4.1 均衡器  
> 16.4.2 修改塊大小  
> 16.4.3 移動塊  
> 16.4.4 特大塊  
> 16.4.5 刷新配置  
