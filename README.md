# PaperFilter

## Introduction

PaperFilter is a project designed to filter and classify research papers based on their relevance to a specified domain. This tool leverages a Large Language Model (LLM) to analyze paper abstracts and determine their alignment with the user's specified area of interest. The core functionality involves prompting the LLM with paper abstracts and receiving responses that classify the papers as relevant or not, along with explanations.

## Key Features

- **Domain-Specific Filtering**: The system can classify papers based on specific research domains, ensuring that only relevant papers are considered.
- **Automated Classification**: Utilizes an advanced LLM to automatically interpret the relevance of papers, reducing the manual effort required for initial filtering.
- **Detailed Responses**: For each paper, the system provides a classification along with a detailed explanation, aiding in understanding the reasoning behind the classification.

<!-- ## Core Functionality

The main function, `classify_papers`, takes a list of paper abstracts and a target domain, then uses the LLM to classify each abstract. The results, including the paper text and the model's response, are saved in a JSON file for further analysis.

## Installation and Setup

1. **Clone the Repository**:
   ```
   git clone <repository_url>
   cd PaperFilter
   ```

2. **Install Dependencies**:
   Ensure you have Python and the necessary libraries installed. Use the following command to install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. **Run the Script**:
   Modify the `papers` and `domain` variables in the script to your dataset and domain of interest, then run the script.

## Future Work

- **Expand Domain Coverage**: Include support for more specialized domains.
- **Improve Classification Accuracy**: Enhance the LLM's ability to interpret and classify papers accurately.
- **User Interface**: Develop a user-friendly interface for easier interaction and analysis.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details. -->