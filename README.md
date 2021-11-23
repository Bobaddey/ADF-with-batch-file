# ADF-with-batch-file
Configuring Azure Datafactory with Azure Batch

* I'll be demonstrating how to run Large workloads on Azure Batch using Azure Data Factory.
Follow me!

# Set up
* An Azure Batch account
* A Storage account
* An ADF pipeline
* A python script (Can have basically just an "Hell World"

#Step 1 ( Creating an Azure Batch Account)

* Create a Azure batch account in a region close to you.
Check the documentation below which gives a step by step guide on how to do this
https://docs.microsoft.com/en-us/azure/batch/batch-account-create-portal#:~:text=%20Create%20a%20Batch%20account%20%201%20Sign,select%20Advanced%20to%20specify%20Identity%20type%2C...%20More%20

#Step 2 (Storage account creation  and container setup)
* Create a Storage account in the *same region as your batch account
Check the documentation below which gives a step by step guide on how to do this
https://docs.microsoft.com/en-us/azure/storage/common/storage-account-create?tabs=azure-portal

* Create a container 
**Following the steps nummerically, you can create a container where your files will be uploaded to.
![container creation](https://user-images.githubusercontent.com/60587384/143048303-3327ae0d-63e9-4e8e-9c02-99ba5205d286.png)
