# Email Response Automation Application
Description:
The Email Response Automation Application uses advanced natural language processing to automate email responses. It employs the "MoritzLaurer/DeBERTa-v3-base-mnli-fever-anli" model for sentiment classification, enabling zero-shot sentiment analysis. 
This state-of-the-art model ensures accurate sentiment detection and generates responses that align with the emotional tone of the emails, demonstrating a commitment to nuanced and context-aware communication.

Overview:
This application automates the reading and responding to emails by utilizing machine learning models. It allows users to configure custom response prompts via the config.py file, ensuring flexibility in automating email correspondence.


Code Structure:

* Data: Contains the PDF Knowledge Base for creating the vector database.
* Email_Reader: Handles reading emails from various sources.
   email_reader.py: Reads emails from the specified source.
   email_response.py: Processes emails and drafts responses.
* Logs: Stores execution logs.
* Utils: Contains utility scripts for the application.
  loaders.py: Manages data and model loading.
  logging.py: Provides logging functionality.
  text_processing.py: Handles text preprocessing and analysis.
  vector_db.py: Manages vector database operations.
  vectorstores.py: Oversees vector storage.
* config.py: Configuration file for setting custom prompts.
* ingest.py: Processes data to create the vector database.
* interface.py: Defines the Gradio app interface.
* requirements.txt: Lists dependencies required for the application.
  
Configuration:
Customize the email response prompts by editing the config.py file. This allows for tailoring the automation process to meet specific email correspondence needs.

Vector Database:
Run the ingest.py script to create and maintain the vector database, which is essential for efficient email analysis and processing.

Gradio App:
Launch the Gradio interface by running interface.py. This user-friendly interface facilitates interaction with the email automation system.

Getting Started:

1) Install the required dependencies:
- pip install -r requirements.txt

2) Configure your email data source and customize the config.py file with your prompts.
3) Use ingest.py to create the vector database.
4) Run interface.py to start the Gradio interface and begin automating email responses.
   
Links
1) Learn more about Ollama.
2) Discover Langchain.
