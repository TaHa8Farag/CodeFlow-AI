# CodeFlow AI

## Description
CodeFlow AI is an innovative tool designed to streamline the process of code evaluation and improvement. Leveraging the power of GPT-3.5 Turbo, this application provides real-time feedback on code effectiveness, performance, readability, and adherence to clean code principles.

## Features
- **AI-Powered Code Review**: Uses OpenAI's GPT-3.5 Turbo to analyze and provide feedback on code snippets.
- **Streamlit Interface**: Provides a user-friendly web interface built with Streamlit for submitting tasks and viewing AI-generated evaluations.
- **Integration with Local Development**: Utilizes Pyngrok to tunnel local servers to the internet, facilitating easy access and interaction with the Streamlit application.

## Installation
Install the necessary libraries to set up your development environment:
```bash
pip install openai streamlit pyngrok
```

## Setup and Usage
### Setting up the Streamlit Application
Create a Python file named `app.py` to configure the Streamlit UI and integrate with OpenAI for code evaluation:
```python
# app.py content goes here
```
Configure your OpenAI API key and set up the Streamlit interface to accept code submissions and display evaluations.

### Running the Application
Run the Streamlit application and expose it using Pyngrok:
```bash
streamlit run app.py &>/dev/null &
!npx localtunnel --port 8501
```
This command runs the application and provides a URL to access it through a browser.

## Usage Instructions
- **Start the Application**: Navigate to the provided localtunnel URL to access the CodeFlow AI interface.
- **Submit Code**: Enter your task description and code solution in the respective text areas.
- **Generate Feedback**: Click the "Generate Feedback" button to receive comprehensive AI-generated insights on the submitted code.

## Contributing
Contributions to CodeFlow AI are welcome! Feel free to fork the repository, make your improvements, and submit a pull request.

## License
CodeFlow AI is open-sourced under the Apache License 2.0.

## Contact
For more information or queries, please contact tahafarag111@gmail.com.
