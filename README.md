# **Blog Generation App**

## **Overview**
The **Blog Generation App** is a simple web application built with Streamlit that generates blogs using the Llama 2 language model. Users can input a blog topic, specify the number of words, and select the target audience (blog style) to get a customized blog generated in real-time.

---

## **Features**
- **Custom Blog Generation**: Create blogs tailored to specific job profiles or audiences such as Researchers, Data Scientists, or Common People.
- **Dynamic Input Fields**: Input your blog topic, number of words, and audience type for a personalized output.
- **Powered by Llama 2**: Utilizes the Llama 2 language model for high-quality text generation.

---

## **Technologies Used**
- **Python**: Core programming language.
- **Streamlit**: Framework for building the web interface.
- **LangChain**: Used for prompt templates.
- **CTransformers**: Integration with Llama 2 model.
- **Llama 2**: Open-source large language model for generating text.

---

## **Setup Instructions**

### **Prerequisites**
- Python 3.9+
- A compatible version of the Llama 2 model file: `llama-2-7b-chat.ggmlv3.q8_0.bin`
- Necessary Python libraries:
  - `streamlit`
  - `langchain`
  - `langchain_community`
  - `ctransformers`

### **Steps to Run**
1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/blog-generation-app.git
   cd blog-generation-app
