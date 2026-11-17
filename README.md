<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Streamlit%20ML%20Showcase&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Interactive%20Machine%20Learning%20%7C%20Computer%20Vision%20%7C%20LangChain%20RAG&descSize=16&descAlignY=58&descColor=ffffff"/>

</div>

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-14354C?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-00599C?style=for-the-badge&logoColor=white)

<br/>

### A curated collection of interactive Machine Learning, Deep Learning, and AI applications built with Streamlit.

<br/>

**[📂 Projects](#-projects) · [🏗️ Structure](#%EF%B8%8F-project-structure) · [🚀 Getting Started](#-getting-started) · [⚙️ Tech Stack](#%EF%B8%8F-tech-stack)**

</div>

---

## 📂 Projects

### 📘 1. LangChain & Local LLM RAG Assistant
An interactive Q&A assistant built with LangChain, FAISS vector search, and local Gemma-2 via Ollama. Allows querying domain knowledge documents with conversational memory and retrieval feedback.

- **Stack**: LangChain, FAISS, HuggingFace Embeddings (`all-MiniLM-L6-v2`), Ollama (`gemma2:2b`), Streamlit
- **Directory**: `01_langchain_rag_cpp/`
- **Modules**:
  - `cpp_rag_assistant.py`: Full interactive RAG assistant with Ollama Gemma-2 and passage viewer
  - `cpp_qa_chatbot.py`: Prompt-engineered single-turn Q&A chatbot
  - `cpp_similarity_search.py`: Lightweight semantic similarity inspection demo

---

### 🧠 2. CNN Image Classifier & Live Trainer
A complete computer vision app to train and evaluate Convolutional Neural Networks directly from the browser. Supports built-in benchmarks as well as custom dataset uploads.

- **Features**:
  - Benchmark training on CIFAR-10 with real-time loss & accuracy curve visualization.
  - Custom dataset upload via zip archives with automatic directory parsing.
  - Interactive prediction mode: upload any test image and receive top-predicted class with confidence score.
- **Stack**: TensorFlow, Keras, Matplotlib, Streamlit
- **Directory**: `02_cnn_image_classifier/`
- **Modules**:
  - `cnn_classifier_app.py`: Web dashboard for training and inference
  - `cnn_model.py`: Keras Sequential CNN architecture specification

---

### 🎨 3. Streamlit Component Playbook
A hands-on reference implementation demonstrating essential Streamlit UI paradigms: forms, state handling, reactive charts, file uploaders, and multimedia components.

- **Features**: Dataframe filtering, reactive graphs, form authentication flow, dynamic input widgets.
- **Stack**: Streamlit, Pandas, NumPy
- **Directory**: `03_streamlit_tutorial/`
- **Modules**:
  - `streamlit_showcase_app.py`: Comprehensive Streamlit widget & layout showcase

---

## 🏗️ Project Structure

```
Streamlit-ML-Showcase/
│
├── 📘 01_langchain_rag_cpp/
│   ├── cpp_rag_assistant.py        # Full LangChain + FAISS + Ollama assistant
│   ├── cpp_qa_chatbot.py           # LLM-prompted QA interface
│   ├── cpp_similarity_search.py    # Lightweight similarity search viewer
│   └── Cpp.txt                     # Knowledge base document
│
├── 🧠 02_cnn_image_classifier/
│   ├── cnn_classifier_app.py       # Interactive CNN trainer and classifier UI
│   └── cnn_model.py                # Modular Keras Sequential CNN architecture
│
├── 🎨 03_streamlit_tutorial/
│   └── streamlit_showcase_app.py   # Comprehensive Streamlit widget & layout showcase
│
├── .gitignore
├── requirements.txt
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Soham-Sahana/Streamlit-ML-Showcase.git
cd Streamlit-ML-Showcase
```

### 2. Set up a virtual environment

```bash
# Windows
python -m venv venv
venv\Scripts\activate

# Linux / macOS
python -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Running Any Project

Each project is independent and can be executed with `streamlit run`:

```bash
# Run the LangChain C++ RAG Assistant
streamlit run 01_langchain_rag_cpp/cpp_rag_assistant.py

# Run the CNN Image Classifier
streamlit run 02_cnn_image_classifier/cnn_classifier_app.py

# Run the Streamlit Playbook
streamlit run 03_streamlit_tutorial/streamlit_showcase_app.py
```

> **Note for Local LLM (LangChain RAG):** Ensure [Ollama](https://ollama.ai) is installed and the model is pulled before running:
> ```bash
> ollama run gemma2:2b
> ```

---

## ⚙️ Tech Stack

<div align="center">

| Category | Technologies |
|---|---|
| **Language** | Python 3.10+ |
| **Frontend / Dashboard** | Streamlit |
| **Deep Learning** | TensorFlow, Keras |
| **Vector Retrieval** | FAISS, HuggingFace Sentence-Transformers |
| **LLM Orchestration** | LangChain Core, LangChain Community, Ollama |
| **Data & Plotting** | NumPy, Pandas, Matplotlib |

</div>

---

## 📬 Contact

**Soham Sahana** — [GitHub Profile](https://github.com/Soham-Sahana)

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer"/>

</div>
