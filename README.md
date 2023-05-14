# streamlit-gpt


## Functioning Process

The functioning of the application involves the following steps. Firstly, the PDF is read and its text is divided into smaller sections that are suitable for inputting into a Language Model. OpenAI embeddings are utilized to create vector representations of these sections. Next, the application identifies the sections that exhibit semantic similarity to the user's question and provides those sections as input to the Language Model. The Language Model then generates a response based on the given input.

To develop the graphical user interface (GUI), the application employs Streamlit. Additionally, Langchain is employed to handle the Language Model efficiently.
You will also need to add your OpenAI API key to the `.env` file.

## Usage

To use the application, run the `pdf_explorer.py` file with the streamlit CLI: 

```
streamlit run pdf_explorer.py
```

## Enjoy
