<p align="center"> <img src="https://user-images.githubusercontent.com/91356865/144049159-1ebbd095-87d2-4a3c-81cb-277cc1d4c7b7.png" width="300"> </p> <p align="center"> Starting Up the API Environment on a "Full-of-Beans" SandBox </p>

***

# sap-sandbox  
sap-sandbox は、主にエッジコンピューティング環境において、外部システムをSAPと統合することを目的として作成されたリソースをまとめたリポジトリです。  
sap-sandbox の 「sandbox」は、Netflix 韓国ドラマ 「START-UP」 より、すべての開発者のための 地ならし になればという想いから命名されました。  
なお、各リポジトリのリソースは、そのままクラウド環境におけるアプリケーションにも適用可能です。  

## 前提条件  
sap-sandbox は、オンプレミス版である（＝クラウド版ではない）SAPS4HANA API の利用を前提としています。  
クラウド版APIを利用する場合は、ご注意ください。  

## Latona における SAP 領域・機能ごと の リソース整備状況    
下の図において、チェックマークが付いているリソースが、Latonaにおいて(少なくとも1次の)整備が行われたものであり、github上に公開されています。  

![リソース整備状況](documents/sap_list.drawio(75).png)

## 各リソースの所在  
各リソースの所在は、次の箇所です。  

### Central Functions  
##### EVENTS

* [sap-business-user-events](https://github.com/latonaio/sap-business-user-events)
* [sap-api-integrations-characteristic-events](https://bitbucket.org/latonaio/sap-api-integrations-characteristic-events/src/master/)
* [sap-api-integrations-business-partner-events](https://github.com/latonaio/sap-api-integrations-business-partner-events)

##### READS

* [sap-api-integrations-characteristic-reads](https://github.com/latonaio/sap-api-integrations-characteristic-reads)
* [sap-api-integrations-business-partner-reads](https://github.com/latonaio/sap-api-integrations-business-partner-reads)
##### SQL

* [sap-business-partner-sql](https://github.com/latonaio/sap-business-partner-sql)
* [sap-characteristic-sql](https://bitbucket.org/latonaio/sap-characteristic-sql/src/master/)

### Logistics  
##### EVENTS

* [sap-api-integrations-product-master-events](https://github.com/latonaio/sap-api-integrations-product-master-events)  
* [sap-api-integrations-batch-master-record-events](https://github.com/latonaio/sap-api-integrations-batch-master-record-events)

##### READS

* [sap-api-integrations-product-master-reads](https://github.com/latonaio/sap-api-integrations-product-master-reads) 
* [sap-api-integrations-product-master-classification-reads](https://bitbucket.org/latonaio/sap-api-integrations-product-master-classification-reads/src/master/) 
* [sap-api-integrations-batch-master-record-reads](https://github.com/latonaio/sap-api-integrations-batch-master-record-reads)

##### SQL

* [sap-product-master-sql](https://github.com/latonaio/sap-product-master-sql)  
* [sap-batch-master-record-sql](https://github.com/latonaio/sap-batch-master-record-sql)  

### Inventory Management  
##### EVENTS

* [sap-api-integrations-inbound-delivery-events](https://github.com/latonaio/sap-api-integrations-inbound-delivery-events)  
* [sap-api-integrations-material-document-events](https://github.com/latonaio/sap-api-integrations-material-document-events)  

##### READS

* [sap-api-integrations-material-stock-reads](https://github.com/latonaio/sap-api-integrations-material-stock-reads)
* [sap-api-integrations-reservation-document-reads](https://github.com/latonaio/sap-api-integrations-reservation-document-reads) 
* [sap-api-integrations-inbound-delivery-reads](https://github.com/latonaio/sap-api-integrations-inbound-delivery-reads)
* [sap-api-integrations-material-document-reads](https://github.com/latonaio/sap-api-integrations-material-document-reads)  

##### SQL

* [sap-material-stock-sql](https://github.com/latonaio/sap-material-stock-sql)  
* [sap-reservation-document-sql](https://github.com/latonaio/sap-reservation-document-sql)  
* [sap-inbound-delivery-sql](https://github.com/latonaio/sap-inbound-delivery-sql)
* [sap-material-document-sql](https://github.com/latonaio/sap-material-document-sql)

### Sales Management
##### EVENTS

* [sap-api-integrations-business-partner-events](https://github.com/latonaio/sap-api-integrations-business-partner-events)
* [sap-api-integrations-sales-pricing-events](https://github.com/latonaio/sap-api-integrations-sales-pricing-events)
* [sap-api-integrations-sales-inquiry-events](https://github.com/latonaio/sap-api-integrations-sales-inquiry-events)
* [sap-api-integrations-sales-quotation-events](https://github.com/latonaio/sap-api-integrations-sales-quotation-events)
* [sap-api-integrations-sales-order-events](https://github.com/latonaio/sap-api-integrations-sales-order-events)  
* [sap-api-integrations-sales-contract-events](https://github.com/latonaio/sap-api-integrations-sales-contract-events)
* [sap-api-integrations-sales-scheduling-agreement-events](https://github.com/latonaio/sap-api-integrations-sales-scheduling-agreement-events)
* [sap-api-integrations-outbound-delivery-events](https://github.com/latonaio/sap-api-integrations-outbound-delivery-events) 
* [sap-api-integrations-customer-return-events](https://github.com/latonaio/sap-api-integrations-customer-return-events)  
* [sap-api-integrations-billing-document-events](https://github.com/latonaio/sap-api-integrations-billing-document-events)  

##### READS

* [sap-api-integrations-business-partner-reads-customer](https://github.com/latonaio/sap-api-integrations-business-partner-reads-customer)  
* [sap-api-integrations-sales-pricing-reads](https://github.com/latonaio/sap-api-integrations-sales-pricing-reads)
* [sap-api-integrations-sales-inquiry-reads](https://github.com/latonaio/sap-api-integrations-sales-inquiry-reads)
* [sap-api-integrations-sales-quotation-reads](https://github.com/latonaio/sap-api-integrations-sales-quotation-reads)
* [sap-api-integrations-sales-order-reads](https://github.com/latonaio/sap-api-integrations-sales-order-reads)
* [sap-api-integrations-sales-contract-reads](https://github.com/latonaio/sap-api-integrations-sales-contract-reads)
* [sap-api-integrations-sales-scheduling-agreement-reads](https://github.com/latonaio/sap-api-integrations-sales-scheduling-agreement-reads)
* [sap-api-integrations-outbound-delivery-reads](https://github.com/latonaio/sap-api-integrations-outbound-delivery-reads)  
* [sap-api-integrations-billing-document-reads](https://github.com/latonaio/sap-api-integrations-billing-document-reads)

##### SQL

* [sap-business-partner-sql](https://github.com/latonaio/sap-business-partner-sql)  
* [sap-sales-pricing-sql](https://github.com/latonaio/sap-sales-pricing-sql)  
* [sap-sales-inquiry-sql](https://github.com/latonaio/sap-sales-inquiry-sql)
* [sap-sales-quotation-sql](https://github.com/latonaio/sap-sales-quotation-sql)
* [sap-sales-order-sql](https://github.com/latonaio/sap-sales-order-sql)  
* [sap-sales-contract-sql](https://github.com/latonaio/sap-sales-contract-sql)
* [sap-sales-scheduling-agreement-sql](https://github.com/latonaio/sap-sales-scheduling-agreement-sql)
* [sap-outbound-delivery-sql](https://github.com/latonaio/sap-outbound-delivery-sql)  
* [sap-billing-document-sql](https://github.com/latonaio/sap-billing-document-sql)  

### Procurement Management  
##### EVENTS

* [sap-api-integrations-business-partner-events](https://github.com/latonaio/sap-api-integrations-business-partner-events)  
* [sap-api-integrations-purchasing-info-record-events](https://github.com/latonaio/sap-api-integrations-purchasing-info-record-events)  
* [sap-api-integrations-purchase-requisition-events](https://github.com/latonaio/sap-api-integrations-purchase-requisition-events) 
* [sap-api-integrations-purchase-order-events](https://github.com/latonaio/sap-api-integrations-purchase-order-events)  
* [sap-api-integrations-purchase-contract-events](https://github.com/latonaio/sap-api-integrations-purchase-contract-events)
* [sap-api-integrations-purchase-scheduling-agreement-events](https://github.com/latonaio/sap-api-integrations-purchase-scheduling-agreement-events)
* [sap-api-integrations-supplier-invoice-events](https://github.com/latonaio/sap-api-integrations-supplier-invoice-events)

##### READS

* [sap-api-integrations-business-partner-reads-supplier](https://github.com/latonaio/sap-api-integrations-business-partner-reads-supplier)  
* [sap-api-integrations-purchasing-source-list-reads](https://github.com/latonaio/sap-api-integrations-purchasing-source-list-reads)  
* [sap-api-integrations-purchasing-info-record-reads](https://github.com/latonaio/sap-api-integrations-purchasing-info-record-reads)  
* [sap-api-integrations-purchase-requisition-reads](https://github.com/latonaio/sap-api-integrations-purchase-requisition-reads)
* [sap-api-integrations-purchase-order-reads](https://github.com/latonaio/sap-api-integrations-purchase-order-reads)  
* [sap-api-integrations-purchase-contract-reads](https://github.com/latonaio/sap-api-integrations-purchase-contract-reads)
* [sap-api-integrations-purchase-scheduling-agreement-reads](https://github.com/latonaio/sap-api-integrations-purchase-scheduling-agreement-reads)
* [sap-api-integrations-supplier-invoice-reads](https://github.com/latonaio/sap-api-integrations-supplier-invoice-reads)

##### SQL  

* [sap-business-partner-sql](https://github.com/latonaio/sap-business-partner-sql)
* [sap-purchasing-source-list-sql](https://github.com/latonaio/sap-purchasing-source-list-sql)  
* [sap-purchasing-info-record-sql](https://github.com/latonaio/sap-purchasing-info-record-sql) 
* [sap-purchase-requisition-sql](https://github.com/latonaio/sap-purchase-requisition-sql) 
* [sap-purchase-order-sql](https://github.com/latonaio/sap-purchase-order-sql)
* [sap-purchase-contract-sql](https://github.com/latonaio/sap-purchase-contract-sql)
* [sap-purchase-scheduling-agreement-sql](https://github.com/latonaio/sap-purchase-scheduling-agreement-sql)
* [sap-supplier-invoice-sql](https://github.com/latonaio/sap-supplier-invoice-sql)

### Production Management  
##### EVENTS

* [sap-api-integrations-bill-of-material-events](https://github.com/latonaio/sap-api-integrations-bill-of-material-events)  
* [sap-api-integrations-work-center-events](https://github.com/latonaio/sap-api-integrations-work-center-events) 
* [sap-api-integrations-production-order-events](https://github.com/latonaio/sap-api-integrations-production-order-events)  

##### READS

* [sap-api-integrations-bill-of-material-reads](https://github.com/latonaio/sap-api-integrations-bill-of-material-reads)  
* [sap-api-integrations-work-center-reads](https://github.com/latonaio/sap-api-integrations-work-center-reads)
* [sap-api-integrations-production-routing-reads](https://github.com/latonaio/sap-api-integrations-production-routing-reads)   
* [sap-api-integrations-planned-independent-requirement-reads](https://github.com/latonaio/sap-api-integrations-planned-independent-requirement-reads)  
* [sap-api-integrations-material-planning-data-reads](https://github.com/latonaio/sap-api-integrations-material-planning-data-reads) 
* [sap-api-integrations-planned-order-reads](https://github.com/latonaio/sap-api-integrations-planned-order-reads)
* [sap-api-integrations-production-order-reads](https://github.com/latonaio/sap-api-integrations-production-order-reads)  
* [sap-api-integrations-production-order-confirmation-reads](https://github.com/latonaio/sap-api-integrations-production-order-confirmation-reads) 

##### SQL 

* [sap-bill-of-material-sql](https://github.com/latonaio/sap-bill-of-material-sql)  
* [sap-work-center-sql](https://github.com/latonaio/sap-work-center-sql)  
* [sap-production-routing-sql](https://github.com/latonaio/sap-production-routing-sql)  
* [sap-material-planning-data-sql](https://github.com/latonaio/sap-material-planning-data-sql)  
* [sap-planned-independent-requirement-sql](https://github.com/latonaio/sap-planned-independent-requirement-sql)  
* [sap-planned-order-sql](https://github.com/latonaio/sap-planned-order-sql)
* [sap-production-order-sql](https://github.com/latonaio/sap-production-order-sql)   

### Plant Management  
##### EVENTS

* [sap-api-integrations-equipment-master-events](https://github.com/latonaio/sap-api-integrations-equipment-master-events) 

##### READS

* [sap-api-integrations-equipment-master-reads](https://github.com/latonaio/sap-api-integrations-equipment-master-reads)

##### SQL 

* [sap-equipment-master-sql](https://github.com/latonaio/sap-equipment-master-sql)  

### Customer Service
##### EVENTS

* [sap-api-integrations-service-order-events](https://github.com/latonaio/sap-api-integrations-service-order-events)

##### READS

* [sap-api-integrations-service-order-reads](https://github.com/latonaio/sap-api-integrations-service-order-reads)

##### SQL

* [sap-service-order-sql](https://github.com/latonaio/sap-service-order-sql)

## sap-sandbox における SAP領域・機能 の選択基準
sap-sandbox におけるSAP領域・機能は、SAP S4HANA のあらゆる領域・機能のうち、世界中の企業で繰り返し利用される、利用頻度の高いものと判断されるものが、選択されています。  

## SQL 作成の基準
sap-sandbox において ある機能 に対して SQL を 作成するかどうか は、次の基準に基づいて判断されています。  

* 外部システム側で当該機能の必要十分なデータ量を保持する要求が、平均的にあるかどうか  
* 当該機能の平均的要求に、外部システムから帳票を出力することが含まれるかどうか  

上記基準のいずれかに当てはまれば、sap-sandbox において SQL が作成され、該当するレポジトリが存在します。  
なお、SAP API Business Hub にて READ API が公開されていない機能については、sap-sandbox において SQL は作成されません。  


## Rededgeとの依存関係  
以下の図は、sap-sandbox と [rededge](https://github.com/latonaio/rededge) との依存関係を示した図です。（sap-sandbox は マイクロサービス であり、rededge と独立して動作します。rededge と組み合わせないと機能しないということではありません）    
SAP-SANDBOX は、REDEDGE との統合に関連して、以下の機能を提供します。  

* Full Coverage of SAP S4HANA APIs（SAP S4HANA API の完全なカバレッジ）    
* Frexibly Mixed Golang / Kubernetes Runtime for API Callers（API Caller のための フレキシブルに組み合わせ可能な Golang / Kubernetes ランタイム）   
* Fragmented and Microservicized Parts（細かく刻まれマイクロサービス化された部品）  
* Nascently Styled API Formats and SQL Sheets（新生にスタイルされた APIフォーマット と SQLシート）  
* Latest! Always Latest!（リソースは常に最新の状態です！）  

![rededge_sap](documents/rededge_sap.drawio.png)  
