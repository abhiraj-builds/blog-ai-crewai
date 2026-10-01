# 🤖 AI Blog Generator using CrewAI

An AI-powered blog generation project built using **CrewAI, LangChain, and Groq**.

The project uses multiple AI agents working in a sequential workflow to generate a blog from a user-provided topic.

## 🚀 Features

- Generate blogs from a given topic
- Multi-agent AI workflow using CrewAI
- Content planning
- Blog writing
- Content editing
- Sequential agent execution
- Groq-powered LLM integration

## 🔄 How It Works

The project follows a sequential multi-agent workflow:

```text
User enters a blog topic
        ↓
Content Planner Agent
        ↓
Content Writer Agent
        ↓
Editor Agent
        ↓
Final Blog
```

Each agent performs a specific task and passes its output to the next agent.

## 🛠️ Technologies Used

- Python
- CrewAI
- LangChain
- LangChain-Groq
- Groq LLM
- Jupyter Notebook / Google Colab

## 📁 Project Structure

```text
blog-ai-crewai/
│
├── BLOG_AI.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/blog-ai-crewai.git
cd blog-ai-crewai
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## 🔑 API Key

The project requires a **Groq API key** to run the language model.

When running the notebook, provide your API key when prompted.

**Never upload or commit your actual API key to GitHub.**

## ▶️ Running the Project

You can run the project using **Google Colab** or **Jupyter Notebook**.

Open:

```text
BLOG_AI.ipynb
```

Run the cells and enter the blog topic when prompted.

Example:

```text
Enter the blog topic: Artificial Intelligence in Education
```

The AI agents will then work sequentially to generate the final blog.

## 🎯 Project Objective

The objective of this project is to demonstrate how multiple specialized AI agents can collaborate through a structured workflow to automate blog creation.

## 🔮 Future Improvements

- Build a Streamlit web interface
- Add blog download functionality
- Add multiple writing styles
- Add customizable blog length
- Add support for multiple languages
- Deploy the application online

## 👨‍💻 Author

**Abhiraj Kumar**

B.Tech Information Technology  
2028 Batch