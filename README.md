# Question-Answer-Generation-Pipeline-with-LLM
This project focuses on generating question-answer pairs from text data using a language model (TheBloke/Mistral-7B-Instruct-v0.1-GGUF). It involves merging data from multiple CSV files, preprocessing the text, and leveraging an LLM to automatically create relevant question-answer pairs.
# Key Contributions
## CSV Data Merging:
Wrote scripts to merge data from news articles and reviews stored in CSV files into a single dataset.
## Question-Answer Generation: 
Implemented a pipeline to generate question-answer pairs from the merged text data using the Mistral-7B large language model.
## Documentation: 
Documented installation, usage, and project structure for user clarity.
# Installation
clone the repository:
git clone https://github.com/Iqra9999/Question-Answer-Generation-Pipeline-with-LLM

cd qa-generation

install the necessary packages:
pip install -r requirements.txt
# Usage
You can easily run the script with your own CSV files containing text data. Ensure your CSV files follow a similar format to the provided examples.

After merging your CSV files, you can generate question-answer pairs using the Mistral 7-B language model.

If your CSV file contains multiple columns and you want to generate question-answer pairs from specific columns, you can preprocess your data accordingly. 
# Contributions
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
# License
This project is licensed under the MIT License. See the LICENSE file for details.
