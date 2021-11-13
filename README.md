# sap-sandbox  
sap-sandbox は、主にエッジコンピューティング環境において、外部システムをSAPと統合することを目的として作成されたリソースをまとめたリポジトリです。  
sap-sandbox の 「sandbox」は、韓国ドラマ「start-up」より、すべての開発者のための 地ならし になればという想いから命名されました。  
なお、各リポジトリのリソースは、そのままクラウド環境におけるアプリケーションにも適用可能です。  

## 前提条件  
sap-sandbox は、オンプレミス版である（＝クラウド版ではない）SAPS4HANA API の利用を前提としています。  
クラウド版APIを利用する場合は、ご注意ください。  

## Latona における SAP 領域・機能ごと の リソース整備状況    
下の図において、チェックマークが付いているリソースが、Latonaにおいて(少なくとも1次の)整備が行われたものであり、github上に公開されています。  

![リソース整備状況](documents/sap_sandbox_1113.png)

## 各リソースの所在  
各リソースの所在は、次の箇所です。  

### Logistics  

* [sap-api-integrations-product-master-events](https://github.com/latonaio/sap-api-integrations-product-master-events)  
* [sap-api-integrations-product-master](https://github.com/latonaio/sap-api-integrations-product-master) 
* [sap-product-master-sql](https://github.com/latonaio/sap-product-master-sql)  
* [sap-api-integrations-batch-master-record-events](https://github.com/latonaio/sap-api-integrations-batch-master-record-events)  
* [sap-batch-master-record-sql](https://github.com/latonaio/sap-batch-master-record-sql)  

### Inventory Management  

* [sap-api-integrations-material-stock-reads](https://github.com/latonaio/sap-api-integrations-material-stock-reads)  
* [sap-material-stock-sql](https://github.com/latonaio/sap-material-stock-sql)  
* [sap-api-integrations-reservation-document-reads](https://github.com/latonaio/sap-api-integrations-reservation-document-reads)  
* [sap-reservation-document-sql](https://github.com/latonaio/sap-reservation-document-sql)  
* [sap-api-integrations-inbound-delivery-events](https://github.com/latonaio/sap-api-integrations-inbound-delivery-events)  
* [sap-api-integrations-material-document-events](https://github.com/latonaio/sap-api-integrations-material-document-events)  

### Sales Management

* [sap-api-integrations-business-partner-events](https://github.com/latonaio/sap-api-integrations-business-partner-events)
* [sap-api-integrations-business-partner-reads](https://github.com/latonaio/sap-api-integrations-business-partner-reads)
* [sap-business-partner-sql](https://github.com/latonaio/sap-business-partner-sql)  
* [sap-api-integrations-sales-pricing-condition-record-events](https://github.com/latonaio/sap-api-integrations-sales-pricing-condition-record-events)
* [sap-api-integrations-sales-order-events](https://github.com/latonaio/sap-api-integrations-sales-order-events)  
* [sap-api-integrations-outbound-delivery-events](https://github.com/latonaio/sap-api-integrations-outbound-delivery-events)  
* [sap-outbound-delivery-sql](https://github.com/latonaio/sap-outbound-delivery-sql)
* [sap-api-integrations-billing-document-events](https://github.com/latonaio/sap-api-integrations-billing-document-events)  
* [sap-billing-document-sql](https://github.com/latonaio/sap-billing-document-sql)  

### Procurement Management  

* [sap-api-integrations-business-partner-events](https://github.com/latonaio/sap-api-integrations-business-partner-events)
* [sap-api-integrations-business-partner-reads](https://github.com/latonaio/sap-api-integrations-business-partner-reads)
* [sap-business-partner-sql](https://github.com/latonaio/sap-business-partner-sql)
* [sap-api-integrations-purchasing-info-record-reads](https://github.com/latonaio/sap-api-integrations-purchasing-info-record-reads)  
* [sap-purchasing-info-record-sql](https://github.com/latonaio/sap-purchasing-info-record-sql)  
* [sap-api-integrations-purchase-requisition-events](https://github.com/latonaio/sap-api-integrations-purchase-requisition-events)  
* [sap-api-integrations-purchase-order-events](https://github.com/latonaio/sap-api-integrations-purchase-order-events)  
* [sap-purchasing-source-list-sql](https://github.com/latonaio/sap-purchasing-source-list-sql)  

### Production Management  

* [sap-api-integrations-bill-of-material-events](https://github.com/latonaio/sap-api-integrations-bill-of-material-events)  
* [sap-api-integrations-bill-of-material-reads](https://github.com/latonaio/sap-api-integrations-bill-of-material-reads)  
* [sap-bom-sql](https://github.com/latonaio/sap-bom-sql)  
* [sap-api-integrations-work-center-events](https://github.com/latonaio/sap-api-integrations-work-center-events)  
* [sap-work-center-sql](https://github.com/latonaio/sap-work-center-sql)  
* [sap-api-integrations-production-routing-reads](https://github.com/latonaio/sap-api-integrations-production-routing-reads)  
* [sap-production-routing-sql](https://github.com/latonaio/sap-production-routing-sql)  
* [sap-material-planning-data-sql](https://github.com/latonaio/sap-material-planning-data-sql)  
* [sap-planned-independent-requirement-sql](https://github.com/latonaio/sap-planned-independent-requirement-sql)  
* [sap-api-integrations-production-order-events](https://github.com/latonaio/sap-api-integrations-production-order-events)  
* [sap-api-integrations-production-order-reads](https://github.com/latonaio/sap-api-integrations-production-order-reads)  
* [sap-production-order-sql](https://github.com/latonaio/sap-production-order-sql)  
* [sap-api-integrations-production-order-confirmation](https://github.com/latonaio/sap-api-integrations-production-order-confirmation)  

### Plant Management  

* [sap-api-integrations-equipment-master-events](https://github.com/latonaio/sap-api-integrations-equipment-master-events)  
* [sap-equipment-master-sql](https://github.com/latonaio/sap-equipment-master-sql)  
