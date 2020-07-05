
## Prerequisites:

Deploy an Azure Storage account with a container.

#### Paramerters
1. Storage Account Name
2. Container Name


[![Deploy Pre-requisites to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Finsidero%2FAzure-Data-Solutions-ARM-Templates%2Fmaster%2F101-Azure-Storage-with-container%2Fstorage_account_with_container_arm_template.json)

- Data to be copied should be placed in 
  [adf-arm-demo/input]
- The adf-arm-demo/output folder is automatically generated when the pipeline is triggered.

## Azure Data Factory

[![Deploy ADF with Pipeline to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Finsidero%2FAzure-Data-Solutions-ARM-Templates%2Fmaster%2F201-Azure-Data-Factory-with-Sample-Pipeline%2Farm_template.json)

This RM template deploys the following resources:-

### Azure Data Factory with following resources
- ADF Pipeline with Copy Data Activity
- Linked Storage Service
- Input CSV Dataset
- Output CSV Dataset

#### ADF Copy Pipeline 

The pipeline copies the data from [conatiner]/input to [container]/output.
