# ideas-texted-to-you
This project contains a single Python file that uses `requests`, `schedule`, `Twilio`, and `langchain` to process a request made to an LLM server. This LLM server generates a list of 5 SaaS ideas and texts it to the user every 3 hours using the `schedule` library and a `while True` loop.
# Prerequisites
Before you begin, ensure you have met the following requirements:
1. You have installed the latest version of `Python3`.
2.  You have installed the following packages: `requests`,`Twilio` , `schedule` and `langchain`
3.  You have installed `Ollama` using Windows Subsystem for Linux (WSL) with this command: `curl https://ollama.ai/install.sh | sh`
# Installing ideas-texted-to-you
To install ideas-texted-to-you, follow these steps:
1. Clone the repository to your local machine.
2. Navigate to the directory containing the requirements.txt file.
3. Run `pip install -r requirements.txt` to install the required packages.
Using ideas-texted-to-you
To use ideas-texted-to-you, follow these steps:
1. Start `Ollama` with `ollama serve`
2. Download the local AI model you would like to use (in this case, I used mistral-openorca) with this command: `ollama pull mistral-openorca`.
3. Run the model you just downloaded with `ollama run mistral-openorca`
4. Edit the Python file and change the `account_sid`, the `auth_token`, the `from_='YourTwilioPhoneNum'`, and the `to='YourPhoneNum'` to your information.
5. Run the Python file using `python text-list.py`.
6. The LLM server will generate a list of 5 SaaS ideas and text them to the user every 3 hours.
# Contributing to ideas-texted-to-you
To contribute to ideas-texted-to-you, follow these steps:
1. Fork this repository.
2. Create a branch: `git checkout -b <branch_name>`.
3. Make your changes and commit them: `git commit -m '<commit_message>'`
4. Push to the original branch: `git push origin ideas-texted-to-you`
5. Create the pull request.
# Contact
If you want to contact me you can reach me at jaxcreatesstuff@gmail.com.
