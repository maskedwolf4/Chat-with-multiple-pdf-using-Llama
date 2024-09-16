# Chat-with-multiple-pdf-using-Llama

## **README: Multi-PDF Chat Application with Llama3.1-70b LLM and Groq API**

**Project Overview**

This repository contains the code for a Streamlit-based application that enables users to chat with multiple PDFs using the Llama LLM. The application leverages the Groq API for efficient inference, and employs LangChain for tasks like text splitting, embedding, vector database management, and prompt engineering.

**Key Features**

* **Multi-PDF Chat:** Users can interact with multiple PDFs simultaneously, providing a comprehensive conversational experience.
* **Llama LLM:** The application utilizes the powerful Llama LLM for natural language understanding and generation.
* **Groq API:** The Groq API is used to accelerate inference, ensuring faster and more efficient responses.
* **LangChain Integration:** LangChain's capabilities are employed for:
  - Text splitting: Breaking down large PDFs into smaller, manageable chunks.
  - Embeddings: Creating numerical representations of text using HuggingFace embeddings.
  - Vector Database: Storing and retrieving embeddings using FAISS.
  - Chains and Prompts: Orchestrating the interaction between the LLM, embeddings, and vector database.

**Prerequisites**

Before running the application, ensure you have the following installed:

* Python (version 3.10 or later)
* Streamlit
* Llama LLM
* LangChain
* HuggingFace Transformers
* FAISS
* Groq API Key 

**Requirements**

The required libraries are listed in the `requirements.txt` file. Install them using:

```bash
pip install -r requirements.txt
```

**Groq API Key**

To access the Groq API, you'll need an API key. Obtain one from the Groq developer portal and set it as an environment variable in .env file:

```bash
GROQ_API_KEY=your_api_key
```

**Running the Application**

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/maskedwolf4/Chat-with-multiple-pdf-using-Llama.git
   ```
2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Set API Key:**
   Set the `GROQ_API_KEY` environment variable as described above.
4. **Run the Application:**
   ```bash
   streamlit run mpdfcapp.py
   ```

**Usage**

* **Upload PDFs:** Use the provided interface to upload multiple PDF files.
* **Chat:** Interact with the application by typing your questions or prompts. The application will process your input, consult the PDFs, and generate a relevant response.

**Contributing**

We welcome contributions to this project! If you have any improvements or bug fixes, please feel free to submit a pull request.

**License**

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).


