# End-to-end-Medical-Chatbot-Generative-AI

![Screenshot 2025-01-02 052149](https://github.com/user-attachments/assets/01827be4-0f47-401d-865d-6786e386b4c4)

![Screenshot 2025-01-02 052218](https://github.com/user-attachments/assets/1da38803-dd73-4771-a6e4-2fcab2ce9f74)
<<<<<<< HEAD
=======


>>>>>>> 4198d2825042b4c5878d523d48b63d84f9741d06

# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/Ranjeetkuamr/Medical-Chatbot-using-FLAN-T5-Large
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n medical python=3.9 -y
```

```bash
conda activate medical
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

