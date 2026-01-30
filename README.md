🚀 Agentic AI & Generative AI with Hugging Face + Gradio
--> This repository contains a basic Gradio application built using Hugging Face models to demonstrate concepts of Agentic AI and Generative AI.

--> The project showcases how to integrate Hugging Face models into a local environment, manage authentication with access tokens, and run interactive AI demos through Gradio.

--> The project runs directly from a Google Colab notebook integrated with VS Code. When you execute the final cell, the Gradio UI launches automatically in your browser.


⚡ Getting Started
1. Clone the Repository
git clone https://github.com/your-username/agentic-ai-gradio.git
cd agentic-ai-gradio


2. Create a Virtual Environment (venv)
It’s best practice to isolate dependencies using a virtual environment:
# Create venv
python -m venv venv

# Activate venv (Linux/Mac)
source venv/bin/activate

# Activate venv (Windows)
venv\Scripts\activate


3. Install Dependencies
Since this project was developed in Google Colab, install the required libraries manually in your environment:
pip install gradio
pip install transformers
pip install torch   # if using PyTorch-based models


(Add more libraries depending on the Hugging Face model you’re using.)
4. Set Hugging Face Access Token
Generate a token from Hugging Face and set it as an environment variable:
export HUGGINGFACE_TOKEN="your_token_here"


5. Run the Notebook
Open the notebook in VS Code (with Colab integration or Jupyter extension).
Run all cells → the final cell will launch the Gradio UI in your browser.

📂 Project Structure
├── gradio.ipynb      # Main Colab notebook with Gradio app
├── README.md           # Project documentation



🎯 Learnings & Takeaways
- How to use Hugging Face models in Python
- How to generate and manage access tokens securely
- How to integrate Hugging Face with local environments
- How to connect Google Colab with VS Code for flexible development workflows
- How to launch Gradio apps directly from notebooks
