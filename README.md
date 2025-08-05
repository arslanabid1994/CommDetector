Flow of the notebook
The notebook will be divided into separate sections as stated below:
  Importing Python Libraries and preparing the environment
  Importing and Pre-Processing the domain data
  Preparing the Dataset and Dataloader
  Creating the Neural Network for Fine-Tuning
  Fine-Tuning the Model
  Validating the Model Performance
  Saving the model and artifacts for Inference in the Future
  Technical Details

This script leverages multiple tools and libraries. Details of the tools used are as under.

Data:
We are using our newly created dataset, which we have hosted on Google Drive: ECommunication Classification Dataset
We are referring only to the Excel (xlsx) file from the Google Drive folder
There are 83,067 rows of data divided into 2 columns:
Text (The actual communication data)
Class_Label (Class Label)

Language Model Used:
We have used DistilBERT as the classifier. It is a smaller transformer model as compared to BERT or Roberta. It is created by the process of distillation applied to BERT.

Script Objective:
The objective of this script is to fine-tune DistilBERT to be able to classify the data/text into the following categories:
  Normal
  Financial Fraud
  Hate Speech
  Racism
  Religious Abuse
  Sexual Abuse
  Islamophobia
  Terrorism/Violence
  Political_Abuse
