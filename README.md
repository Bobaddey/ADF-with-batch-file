# Run Python scripts through Azure Data Factory using Azure Batch
Configuring Azure Datafactory with Azure Batch

* I'll be demonstrating how to run Large workloads on Azure Batch using Azure Data Factory.
Follow me!

# Set up
* An Azure Batch account
* A Storage account
* An ADF pipeline
* A python script (Can have basically just an "Hell World"

# Step 1 ( Creating an Azure Batch Account)

* Create a Azure batch account in a region close to you.
Check the documentation below which gives a step by step guide on how to do this
https://docs.microsoft.com/en-us/azure/batch/batch-account-create-portal#create-a-batch-account
![image](https://user-images.githubusercontent.com/60587384/143048803-b4d341ad-5eef-4dc6-830c-949c441e36e1.png)


# Step 2 (Storage account creation  and container setup)
* Create a Storage account in the *same region as your batch account
Check the documentation below which gives a step by step guide on how to do this
https://docs.microsoft.com/en-us/azure/storage/common/storage-account-create?tabs=azure-portal

* Create a container 

* Following the steps nummerically, you can create a container where your files will be uploaded to.
![container creation](https://user-images.githubusercontent.com/60587384/143048303-3327ae0d-63e9-4e8e-9c02-99ba5205d286.png)

