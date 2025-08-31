# Prompt Engineering Techniques

**Welcome to the comprehensive Prompt Engineering learning resource!** This repository serves as a practical guide to understanding and implementing effective prompt engineering techniques with Large Language Models (LLMs).

## About This Repository

This repository contains hands-on Jupyter notebooks that demonstrate various prompt engineering principles and techniques. Each notebook provides detailed explanations, practical examples, and code implementations to help you master the art of crafting effective prompts for AI models.

### What You'll Learn

- **Fundamental prompt engineering concepts** and best practices
- **Zero-shot prompting** - Getting quality outputs without examples
- **Multi-shot prompting** - Leveraging examples to guide model behavior  
- **Chain-of-Thought (CoT) prompting** - Breaking down complex reasoning tasks
- **Real-world applications** and use cases
- **Hands-on coding examples** using OpenAI's API

## 🗂️ Repository Structure

```
prompt-engineering/
├── README.md                           # This file
├── requirements.txt                    # Python dependencies
├── pyproject.toml                     # Project configuration
├── uv.lock                           # Dependency lock file
└── prompt-engineering-techniques/    # Core learning materials
    ├── zero-shot-prompting.ipynb     # No-example prompting techniques
    ├── multi-shot-prompting.ipynb    # Few-shot learning with examples
    └── cot-prompting.ipynb           # Chain-of-thought reasoning
```

## 🚀 Getting Started

### Prerequisites

- Python 3.13 or higher
- OpenAI API key (sign up at [OpenAI](https://platform.openai.com/))
- Basic understanding of Python and Jupyter notebooks

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SuperDataScience-Community/prompt-engineering.git
   cd prompt-engineering
   ```

2. **Create and activate virtual environment**

    *For Windows:*

    ```bash
    python -m venv .venv     # create the virtual environment
    .venv\Scripts\Activate   # activate the virtual environment
    ```

    *For Mac/Linux:*

    ```bash
    python3 -m venv .venv       # create the virtual environment
    source .venv/bin/activate   # activate the virtual environment
    ```


3. **Install dependencies:**
   
   Using pip:
   ```bash
   pip install -r requirements.txt
   ```
   
   Or using uv (recommended):
   ```bash
   uv sync
   ```

4. **Set up your OpenAI API key:**
   
   Create a `.env` file in the project root:
   ```bash
   echo "OPENAI_API_KEY=your_api_key_here" > .env
   ```
   
   Replace `your_api_key_here` with your actual OpenAI API key.

5. **Start learning:**
   ```bash
   jupyter notebook prompt-engineering-techniques/
   ```

### Recommended Learning Path

1. **Start with Zero-Shot Prompting** (`zero-shot-prompting.ipynb`)
   - Learn the fundamentals of prompt construction
   - Understand prompt elements: instruction, context, input data, output indicator
   
2. **Progress to Multi-Shot Prompting** (`multi-shot-prompting.ipynb`)
   - Discover how examples improve model performance
   - Learn when and how to use few-shot learning
   
3. **Master Chain-of-Thought Prompting** (`cot-prompting.ipynb`)
   - Break down complex reasoning tasks
   - Implement step-by-step problem solving

## 🛠️ Key Dependencies

- **OpenAI** - For accessing GPT models
- **python-dotenv** - For environment variable management
- **ipykernel** - For Jupyter notebook support


## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

### Ways to Contribute

1. **Report Issues** - Found a bug or have a suggestion? [Open an issue](https://github.com/SuperDataScience-Community/prompt-engineering/issues)
2. **Improve Documentation** - Help make our explanations clearer
3. **Add Examples** - Contribute new prompt engineering techniques or use cases
4. **Fix Bugs** - Submit pull requests for any issues you find

### Contributing Guidelines

1. **Fork the repository** and create a feature branch
2. **Follow the existing code style** and notebook structure
3. **Test your changes** - Ensure all notebooks run successfully
4. **Add clear documentation** - Explain your examples and techniques
5. **Submit a pull request** with a clear description of your changes

### Notebook Guidelines

When contributing notebooks:
- Include clear markdown explanations
- Provide practical, working code examples
- Use consistent naming conventions
- Add relevant comments and docstrings
- Test with the OpenAI API to ensure functionality

## 📚 Additional Resources

- [OpenAI API Documentation](https://platform.openai.com/docs)
- [Prompt Engineering Guide](https://www.promptingguide.ai/)
- [SuperDataScience Community](https://community.superdatascience.com/)

## 📢 Need Help?

### For Issues & Feedback Related to This Repository
- 📧 Open a [GitHub Issue](https://github.com/SuperDataScience-Community/prompt-engineering/issues) or start a [Discussion](https://github.com/SuperDataScience-Community/prompt-engineering/discussions)
- 💬 Join our community: [AI Engineering Q&A](https://community.superdatascience.com/c/ml-ai-questions/)
- 📧 **Email:** shaheer@superdatascience.com

### For Career & General AI Questions
If you have questions about transitioning into AI/Data Science or general questions about the field, feel free to reach out:

- 📧 **Email:** shaheerairajahmed@gmail.com
- 💼 **LinkedIn:** [linkedin.com/in/shaheerairajahmed](https://www.linkedin.com/in/shaheerairajahmed)
- 🐙 **GitHub:** [github.com/shaheerairaj](https://github.com/shaheerairaj)

---

**Happy Learning! 🎉** Start your prompt engineering journey today and unlock the full potential of Large Language Models.