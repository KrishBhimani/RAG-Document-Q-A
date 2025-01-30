# RAG Document Q&A

A robust Retrieval-Augmented Generation (RAG) document Q&A system leveraging the power of **Llama** models and **Hugging Face embeddings**.

## 🚀 Features

- Implements **RAG architecture** for enhanced answer retrieval.
- Uses **Llama model** for generating accurate and contextual responses.
- Employs **Hugging Face embeddings** for efficient document retrieval.
- Built with **LangChain** for seamless orchestration of retrieval and generation.
- Deployed on **Streamlit** for an interactive user interface.

## 🛠️ Installation

### 1️⃣ Clone the Repository

```sh
git clone https://github.com/KrishBhimani/RAG-Document-Q-A.git
```

### 2️⃣ Create a Virtual Environment

#### For Windows:
```sh
python -m venv venv
venv\Scripts\activate
```

#### For macOS/Linux:
```sh
python3 -m venv venv
source venv/bin/activate
```

### 3️⃣ Install Dependencies

```sh
pip install -r requirements.txt
```

### 4️⃣ Set Up Environment Variables

Create a `.env` file in the project root and add:

```ini
GROQ_API_KEY="your_api_key"
HF_TOKEN="your_api_key_here"
LANGCHAIN_API_KEY="your_api_key"
LANGCHAIN_PROJECT="your_project_name_here"
```

Ensure `.env` is excluded from version control by adding it to `.gitignore`.

### 5️⃣ Run the Streamlit App

```sh
streamlit run app.py
```

## 🚀 Deployment on Streamlit Cloud

1. Push the project to GitHub.
2. Go to [Streamlit Cloud](https://share.streamlit.io/).
3. Connect your GitHub repository and select the branch.
4. Add secrets in **Streamlit Settings > Secrets**:
   ```ini
   GROQ_API_KEY="your_api_key"
   HF_TOKEN="your_api_key_here"
   LANGCHAIN_API_KEY="your_api_key"
   LANGCHAIN_PROJECT="your_project_name_here"
   ```
5. Deploy the app and access it online!

### 🌍 Live Demo

Access the deployed app here: **[Streamlit App](https://your-streamlit-app-link)**

