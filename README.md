### EX9 Preprocessing on Twitter Data using Rapidminer
### DATE: 
### AIM: To implement preprocessing technique on Twitter Data using Rapidminer
### Description: 
<div align = "justify">
RapidMiner provides data mining and machine learning procedures including: data loading and transformation (ETL), data preprocessing and visualization, 
predictive analytics and statistical modeling, evaluation, and deployment. RapidMiner is written in the Java programming language. 
RapidMiner provides a GUI to design and execute analytical workflows. Those workflows are called “Processes” in RapidMiner and they consist of multiple “Operators”. 
Each operator performs a single task within the process, and the output of each operator forms the input of the next one. Alternatively, the engine can be called from 
other programs or used as an API. Individual functions can be called from the command line. 
RapidMiner provides learning schemes, models and algorithms and can be extended using R and Python scripts.

### Procedure:
1) ***Import Twitter data:*** Import the Twitter data into RapidMiner. You can do this by selecting the appropriate
data source operator, such as "Read Excel" or "Read CSV," and specifying the location of your Twitter data
file.
2) ***Preprocess data:*** Preprocess the imported data to clean and prepare it for text processing. Use the following
operators for preprocessing:
    <p>a. Tokenize: Split the text into individual words or tokens.
    <p>b. Transform Cases: Convert the text to lowercase or uppercase to ensure consistency.
    <p>c. Remove Stopwords: Remove common words that do not provide much meaningful information.
    <p>d. Remove Special Characters: Eliminate special characters, such as punctuation marks or symbols.
    <p>e. Remove Numbers: Exclude numeric values from the text.
3) ***Stemming:*** Apply stemming to reduce words to their root forms. You can use operators like "Stem (Porter)"
for this purpose.


### Output:
![image](https://github.com/user-attachments/assets/2b9af723-df44-40ae-91b9-80e05cd03425)
![Screenshot 2024-09-13 091123](https://github.com/user-attachments/assets/587bf2f0-9f87-4528-babd-af29b6ec297e)
![Screenshot 2024-09-13 091201](https://github.com/user-attachments/assets/a826d1fb-0477-45ce-8f42-ced5de0603e9)
![Screenshot 2024-09-13 091249](https://github.com/user-attachments/assets/a77a4292-f4f5-4e18-9164-7c5ffba2ad22)
![Screenshot 2024-09-13 091328](https://github.com/user-attachments/assets/ec251fe1-a4be-487b-acaf-e04816634389)
![Screenshot 2024-09-13 091402](https://github.com/user-attachments/assets/62f62c0b-da9a-414e-ae23-dac10b1e8c47)
![Screenshot 2024-09-13 091452](https://github.com/user-attachments/assets/83702d35-62ed-48d8-a49c-8d76fc609280)
![Screenshot 2024-09-13 091634](https://github.com/user-attachments/assets/3b68e45a-6275-4a0c-8abc-25f179e3550f)


### Result:
Thus the implement preprocessing technique on Twitter Data using Rapidminer is executed successfully.
