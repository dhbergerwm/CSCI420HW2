# GenAI for Software Development (Ngram)

---

# **1. Introduction**  
This project fine-tunes, trains, and evaluates an **Pre-Trained Transformer Model** to generate conditional statements when provided with an initial masked method.  

---

# **2. Getting Started**  

This project is implemented in a **Google Colab Notebook** and is viewable and executable on **Google Chrome** or any browser that supports it.  

## **2.1 Preparations**  

(1) Download the necessary files:


**ft_train.csv**


**ft_valid.csv**


**ft_test.csv**


**CSCI420Project2_Final.ipynb** 


**testset-results.csv**

(2) Open **CSCI420Project2_Final.ipynb** in Google Colab

(3) Place **ft_train.csv**, **ft_valid.csv**, and **ft_test.csv** in the **content** (default location) folder of the notebook.

(4) If you do not wish to manually retrain the model, download the **.dill** file at https://drive.google.com/file/d/1ZzZil497U6KmM27QwRTN1wpiHTbtG6dc/view?usp=sharing.

## **2.2 Install Packages**

All package dependencies will be covered by Google Colab itself and the import commands within the notebook.

## **2.3 Run Project**

To run the project, each code block (unless commented out/specified) **must be run in sequential order**. 


If the CSVs (and optionally, the .dill file) are placed within the **content** folder, the code will run from start to finish without issues. Code blocks are commented extensively to highlight key features and nuances of functions or processes.

## **2.4 Run Pre-trained Model**

If the pre-trained model is added to the notebook, the labeled code block will load the **.dill** file and evaluate the stored model instead of retraining.

## **2.5 Generating Files**

If the code is run in sequential order, the **testset-results.csv** will be generated without issue.


If attempting to generate new **.dill** pre-trained model, uncomment the labeled code block, and run it.

## 3. Report

The assignment report is available in the file **GenAI 420 Project 1 Writeup.pdf**.
