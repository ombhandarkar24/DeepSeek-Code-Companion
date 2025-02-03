# **DeepSeek Code Companion**

🧠 **DeepSeek Code Companion** is an AI-powered coding assistant built with **Streamlit**, **LangChain**, and **Ollama**. It provides real-time coding assistance, debugging support, and solution design for developers. The app leverages the **DeepSeek** language model to deliver accurate and concise responses to your coding queries.

---

## **Features**
- 🐍 **Python Expert**: Get expert-level Python coding assistance.
- 🐞 **Debugging Assistant**: Identify and fix bugs in your code.
- 📝 **Code Documentation**: Generate clear and concise documentation for your code.
- 💡 **Solution Design**: Design optimal solutions for your coding problems.
- **Customizable Model**: Choose between different versions of the DeepSeek model (e.g., `deepseek-r1:1.5b`, `deepseek-r1:3b`).

---

## **Requirements**
To run this project, you need the following dependencies:
- Python 3.8 or higher
- Streamlit
- LangChain Core
- LangChain Community
- LangChain Ollama

You can install the required dependencies using the `requirements.txt` file:
```bash
pip install -r requirements.txt

Installation
Clone the Repository:

bash
git clone https://github.com/your-username/deepseek-code-companion.git
cd deepseek-code-companion
Set Up a Virtual Environment (Optional but Recommended):

bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install Dependencies:

bash
pip install -r requirements.txt
Run Ollama Locally:

Ensure Ollama is installed and running on your machine.

Start the Ollama server:

bash
ollama serve
Run the Streamlit App:

bash
streamlit run app.py
Access the App:

Open your browser and navigate to http://localhost:8501.

Usage
Select a Model:

Use the sidebar to choose between different versions of the DeepSeek model (e.g., deepseek-r1:1.5b, deepseek-r1:3b).

Ask Coding Questions:

Type your coding question or problem in the chat input box.

The AI will generate a response with code snippets, debugging tips, or documentation.

View Chat History:

The chat history is displayed in the main container, allowing you to review previous interactions.

File Structure
deepseek-code-companion/
├── app.py                # Streamlit application code
├── README.md             # Project documentation
├── requirements.txt      # List of dependencies
Dependencies
The project relies on the following Python libraries:

Streamlit: For building the web interface.

LangChain Core: For managing the AI pipeline.

LangChain Community: For integrating community-contributed components.

LangChain Ollama: For connecting to the Ollama server.

You can find the full list of dependencies in the requirements.txt file:

streamlit
langchain_core
langchain_community
langchain_ollama
Customization
Model Selection: Modify the selected_model variable in the sidebar to add or remove models.

System Prompt: Update the system_prompt in app.py to customize the AI's behavior.

Styling: Adjust the custom CSS in the st.markdown section to change the app's appearance.

Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

Fork the repository.

Create a new branch (git checkout -b feature/your-feature).

Commit your changes (git commit -m 'Add some feature').

Push to the branch (git push origin feature/your-feature).

Open a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
Built with Ollama and LangChain.

Inspired by the need for efficient coding assistance tools.

Enjoy using DeepSeek Code Companion! If you have any questions or feedback, feel free to open an issue or reach out to the maintainers.

