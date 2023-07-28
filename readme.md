## PIE Engine Online dataset imported in TrainingDML-AI

the steps below to import the dataset in TrainingDML-AI format into the PIE Engine platform for online training is followed:

### Step 1: TrainingDML-AI encoding upload

Log in to the PIE Engine platform and navigate to the dataset management page.
In the dataset tab, click the "New Dataset" option.
Fill in the meta information about the dataset, including dataset name, dataset description, dataset copyright and data accumulation;
Select "Upload in standard format", click "TrainingDML-AI" standard format, and upload the dataset file encoded in TrainDML-AI.
Click the "Upload" button to upload the TrainDML-encoded file to the PIE Engine platform.

![image-20230725163237141](https://github.com/TrainingDML/ImplementationCaseOfPIE/blob/main/img/datasetmetadataupload.png)

### Step 2: TrainingDML-AI data format validation
After uploading, PIE Engine platform will automatically verify the format of the uploaded TrainingDML-AI encoded dataset file.
If the dataset format is correct, the system will display a prompt of successful validation. If there is a format error, the system will provide relevant error information.

![9c34950fc773575b095a5fc5031a2ed2](https://github.com/TrainingDML/ImplementationCaseOfPIE/blob/main/img/tdmlencodingupload.png)

### Step 3: Training data upload
After the format validation is passed, you can choose to preview or view the sample content of the dataset.
After confirming the correctness of the dataset, click the "Upload Dataset" option to import the dataset samples and label data into PIE Engine.
Wait for the dataset to be imported, then you can see the imported dataset in the dataset list of PIE Engine platform.
After completing the above steps, you have successfully imported the TrainingDML-formatted dataset into the PIE Engine platform and are ready to perform online model training on the platform. Please make sure that your TrainingDML-encoded dataset meets the requirements and data format specifications of the PIE Engine platform to ensure smooth import and training.

## PIE Engine online dataset exported as TrainingDML-AI

The process of exporting a dataset existing in the platform to TrainingDML-AI coding format on the PIE Engine platform is as follows:

### Step 1: Select a dataset

Log in to the PIE Engine platform and navigate to the dataset management page.
In the dataset management page, browse or search for the dataset you want to export and select the target dataset.
### Step 2: Export to TrainingDML-AI format

On the selected dataset page, locate and click on the "Export to TDML Format" option.

The system will begin converting the dataset to TraingingDML-AI format. Wait for the export process to complete.

![a795630fd6cddd761e64919f73db9ad9](https://github.com/TrainingDML/ImplementationCaseOfPIE/blob/main/img/export.png)

### Step 3: Download TrainingDML-AI dataset encoding

After the export process is complete, the system will provide a file saving option.

Click on the download link or select Save File to save the TrainingDML-AI format dataset to your local device.
After completing the above three steps, you have successfully exported the existing dataset on the PIE Engine platform to the TrainingDML-AI format. The dataset in the TrainingDML-AI format can now be further processed and utilized on your local machine, e.g., for the training of machine learning models. Please note that the export time may depend on the size and complexity of the dataset.