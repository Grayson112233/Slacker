# Slacker
Simple Slack bot for the Blackbaud Tech Thursday (5/31)
---

This project is an AWS Lambda function that is designed to be triggered by Alexa Skill Kit intents. Run `bash ./build_package.sh` to create the .zip file for Lambda.


### Virtual Environment
It is strongly recommended to use a Python virtual environment. To create a virtual env, use the venv feature of python3. Run the command below in the root project directory. Recommended folder name for the virtual environment is env.
```
python3 -m venv <env-folder-name>
```


To activate that virtual environment, use the command:
```
source <env-folder-name>/bin/activate
```

After activating, to install the dependencies run
```
pip3 install -r requirements.txt
```
