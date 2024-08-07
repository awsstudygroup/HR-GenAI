# HR-Assistant

## Overview
Recruitment-Assistant is a simple demonstration project that leverages Amazon Bedrock and the Anthropic Claude model, integrated with the LangChain library. This project aims to streamline and enhance the recruitment process using advanced AI capabilities. For more details, please refer to the following links:
- [Amazon Bedrock](https://aws.amazon.com/bedrock/)
- [Anthropic Claude 3](https://www.anthropic.com/index/claude-2)

## Setup
To get started with Recruitment-Assistant, follow these steps:

1. **Install Python**:
   - Follow the instructions [here](https://docs.python-guide.org/starting/install3/linux/) to install Python.

2. **Set up a Python virtual environment**:
   - Follow the guide [here](https://docs.python-guide.org/dev/virtualenvs/) to create and activate a virtual environment.

3. **Install AWS CLI**:
   - Follow the quickstart guide [here](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-quickstart.html) to install and configure the AWS CLI.

4. **Clone the Repository**:
   - Open your terminal and run the following commands to clone the repository and navigate into the project directory:
     ```bash
     git clone https://github.com/awsstudygroup/HR-GenAI
     cd HR-GenAI
     ```

5. **Install Required Dependencies**:
   - With your virtual environment activated, run the following command to install the required dependencies:
     ```bash
     pip3 install -r requirements.txt
     ```

6. **Run the Application**:
   - Start the application using Streamlit by running the following command:
     ```bash
     streamlit run Home.py --server.port 8080
     ```

## Architecture
![Architecture](./Architecture.png)

## Learn More About Prompt Design
- [Introduction to Prompt Design](https://docs.anthropic.com/claude/docs/introduction-to-prompt-design)

## Contributing
We welcome contributions to Recruitment-Assistant! Please follow these steps to contribute:

1. **Fork the Repository**:
   - Click the "Fork" button at the top right corner of the repository page to create a copy of the repository in your GitHub account.

2. **Create a New Branch**:
   - Create a new branch for your feature or bugfix:
     ```bash
     git checkout -b feature-or-bugfix-name
     ```

3. **Make Changes**:
   - Make your changes and commit them with clear and descriptive messages:
     ```bash
     git add .
     git commit -m "Description of your changes"
     ```

4. **Push Changes**:
   - Push your changes to your forked repository:
     ```bash
     git push origin feature-or-bugfix-name
     ```

5. **Open a Pull Request**:
   - Open a pull request to the main repository. Provide a clear description of your changes and any relevant context or issues addressed.

## License
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

