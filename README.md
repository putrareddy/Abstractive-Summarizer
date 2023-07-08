## Techgium Hackathon - Abstractive Text Summarization

![image](https://github.com/putrareddy/Abstractive-Summarizer/assets/63699729/cee9f25f-c13e-42fd-bf1b-d1bbfc160697)

This project was developed as part of the Techgium hackathon hosted by L&T Company. It was selected among the top 100 elite teams from over 3,500 competing teams.

### Overview
The focus of this project is abstractive text summarization in the field of computer science. The goal was to develop a highly accurate model that can understand text and generate summaries using its own words, without relying on sentence extraction.

### Key Features
- Leveraged transfer learning techniques, utilizing pre-trained models like BART, to develop a robust system for generating comprehensive summaries.
- Employed BERT to construct an advanced Question and Answer module, ensuring the accuracy of the summaries by comparing answers derived from both the original text and the summary.

### Implementation Details
- Built upon the PyTorch deep learning framework, commonly used in computer science.
- Utilized the versatile CNN-DM Dataset, known for its suitability for natural language processing tasks.
- Seamlessly integrated the transformative Transformers library into the project for efficient processing.
- Created Abstractive Summaries using BART and then extracted all the entities present in Article and Generated Summary to verify whether all the entities present in Generated Summary are present in entities of Article.
- After this, QA model is implemented on Generated Summaries and Questions are generated.
- Based on this questions, answers are generated as entities(one word answers) from both Article and Generated Summary.
- If there is a mismatch, then those entities in Generated Summary are replaced by answer given by Article, Thus improving the accuracy of the model.

### Results
Through dedicated effort and strategic utilization of these resources, our team successfully tackled the challenges of abstractive text summarization. The resulting summaries accurately capture the essence of the source material, while the Q&A module demonstrates their unwavering precision.

### Usage
To use this project, follow the instructions below:

1. Clone the repository.
2. Install the required dependencies listed in the script.
4. Prepare your dataset or use the provided CNN-DM Dataset.
5. Run the main script to train the model and generate summaries.
6. Evaluate the generated summaries using the Question and Answer module.
7. Analyze the results and make improvements based on your requirements.

For more information, please refer to the documentation and code in the repository.

*Note:* This project was developed as a part of the Techgium hackathon and may require additional optimization and customization for specific use cases.
