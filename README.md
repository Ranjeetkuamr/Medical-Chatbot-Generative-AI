# End-to-end-Medical-Chatbot-Generative-AI

![Screenshot 2025-01-02 052149](https://github.com/user-attachments/assets/d99f188f-9a28-4d37-a346-11c8f77fcc3f)

![Screenshot 2025-01-02 052218](https://github.com/user-attachments/assets/1da38803-dd73-4771-a6e4-2fcab2ce9f74)


# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/Ranjeetkuamr/Medical-Chatbot-using-FLAN-T5-Large
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n mchatbot python=3.9 -y
```

```bash
conda activate mchatbot
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


### Create a `.env` file in the root directory and add your Pinecone & openai credentials as follows:

```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
HUGGINGFACE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


```bash
# run the following command to store embeddings to pinecone
python store_index.py
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up localhost:
```


### Techstack Used:

- Python
- LangChain
- Flask
- Flan-t5-large
- Pinecone

