# Azure Modern Data Warehouse Architecture Terraform Template
### Author
Kyle Green
Prodigy Consulting
kgreen@consult-prodigy.com
## Description
Azure's modern data warehouse lets you bring together all your data at any scale easily, and to get insights through analytical dashboards, operational reports, or advanced analytics for all your users. This is accomplished by using a collection of Azure services in unison to provide each layer of functionality. 

The purpose of this solution is to provide an automated and repeatable way to deploy the infrastructure outlined in Microsoft's modern data warehouse architecture. To do this, we're going to utilize HashiCorp's Terraform to templatize the infrastructure. 

More info on the Azure modern data warehouse architecture can be found here: https://docs.microsoft.com/en-us/azure/architecture/solution-ideas/articles/modern-data-warehouse

### Architecture
#### Resources Deployed
- Azure Data Factory
- Azure Data Lake Storage
- Azure Databricks
- Azure Synapse Analytics 
  - Workspace
  - SQL Pool
- Azure Analysis Service

![alt text](https://github.com/kylgrn/tf_azure_mdw/blob/master/Diagram.png)
