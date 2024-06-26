# AI Chatbot Development Using Custom Amazon Toy Dataset

## Project Overview

This project involves developing an AI-driven chatbot using a custom-made Amazon toy dataset derived from an Amazon eCommerce sample dataset. The chatbot utilizes advanced natural language processing (NLP) techniques, including the OpenAI API, OpenAI embedding model Text-embedding-3-small, and Pinecone embedding, to provide accurate and contextually relevant responses.

## Key Features

- Data preprocessing to clean and transform raw dataset
- Implementation of NLP techniques for enhanced understanding and response generation
- Integration with OpenAI API and embedding models
- Deployment using Gradio for an interactive web interface
- Thorough testing and optimization for high accuracy and performance

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- OpenAI API
- OpenAI Embedding Model (Text-embedding-3-small)
- Pinecone Embedding
- Natural Language Processing (NLP)
- Machine Learning (ML)
- Gradio

## Dataset

The dataset used is a custom-made collection of Amazon toy product questions and answers, derived from an Amazon eCommerce sample dataset. It includes:

- **Questions:** Customer inquiries about various toy products.
- **Answers:** Responses to the customer inquiries, often provided by other customers or the product sellers.

## Data Preprocessing

Data preprocessing steps involved:

1. Loading the dataset and removing unnecessary columns such as `uniq_id`, `number_of_reviews`, etc.
2. Combining relevant columns into a single column to consolidate product information.
3. Splitting a combined `QA` column into separate `Question` and `Answer` columns.
4. Handling missing values to maintain data integrity.

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/ai-chatbot-amazon-toy-dataset.git
    cd ai-chatbot-amazon-toy-dataset
    ```

2. Install required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Open the Jupyter notebook for data preprocessing:
    ```bash
    jupyter notebook Data_Preprocessing.ipynb
    ```

4. Open the main chatbot development notebook:
    ```bash
    jupyter notebook Chatbot_(Divine_D).ipynb
    ```

5. Run the notebooks step-by-step to preprocess the data and train the chatbot.

6. To deploy the chatbot using Gradio:
    ```python
    gr.Interface(fn=chatbot_function, inputs="text", outputs="text").launch()
    ```

## Project Outcome

Successfully created a responsive and user-friendly chatbot capable of handling a wide range of product-related queries, providing accurate and helpful responses. This project demonstrates expertise in AI, NLP, and ML, showcasing the ability to develop advanced conversational agents.

## Contributing

Contributions are welcome! Please fork the repository and use a feature branch. Pull requests are gladly accepted.

## License

This project is licensed under the MIT License.

## Contact

For any inquiries, please contact [kunalsingh974@gmail.com].
