# AI project management assistant using rag, llm and vector database


This repository contains code, video explanation and pdf explanation of our project management chatbot. The users can clarify any uncertainties and obtain actionable information that helps them better understand their project's status.

An innovative solution leveraging Prompt Engineering to revolutionize project management processes. Developed by Juilee Patil and Soumya Nayak as part of the Prompt Engineering & AI course.

# Features

- Graphical user interface (GUI) for easy interaction using Streamlit.
- Seamless integration with Pinecone's Managed Cloud Service and rag.
- Simple setup process by cloning the repository
- Fine tuning of the llm

# Prerequisites

Before using, make sure you have the following:

- Python 3.x installed on your system.
- An active Pinecone Managed Cloud Service account.
- Your Pinecone Managed Cloud Service and openai credentials.

# Installation

To install and run the app boilerplate, follow these steps:

1. Clone this repository to your local machine:

```shell
https://github.com/Juileepatil84/Final_Project_prompt.git
```

2. Change into the project directory:

```shell
cd Final_Project_prompt
```

3. Install the required Python packages using pip:

```shell
pip install -r requirements.txt
```
# Host on streamlit cloud

1. Sign Up for Streamlit Sharing: Go to Streamlit Sharing and sign up with your GitHub account.
2. Deploy App: Once logged in, click on ‘New app’, then select your GitHub repository, the branch, and the path to your Streamlit script. 
4. Configure Secrets (if necessary): If your app uses secrets (like API keys), you can add them in the app settings under the ‘Advance settings’ tab.
5. Deploy: Click 'Deploy' to start the deployment process. Streamlit will install the dependencies and launch your app.

# Link to video explanation
https://drive.google.com/file/d/1vJpfN1MNTpGdF60tAQXAvfMx2tPm8vu2/view?usp=sharing

# Link to youtube tutorial
https://youtu.be/iS_PpT4sEjM?si=sMzKrEmZrqoSg4VH

# Link to our website
https://finalprojectprompt.streamlit.app/

# License

The code in this repository is available under the [MIT License]

# Future scope

Integrate project management applications like jira to extract the data and then automate the task assignment.

# Note 

Pinecone free version allows maximum of 5 index. Exceeding that may give error. As this application is a prototype we are using free version
