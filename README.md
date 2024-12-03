# streamlit-python

In this repository, I demonstrate how to deploy a Streamlit app for predicting Titanic survival. The prediction is performed using **XGBoost** based on input fields, determining whether a passenger would survive or not. This project is deployed on **AWS EC2 Instances**.

## Deployment Steps on AWS EC2

### 1. Set Up Your EC2 Instance
- Make sure you have an AWS account.
- Create and configure your EC2 instance.

### 2. Run the Following Commands in Order

```bash
# Update and upgrade system packages
sudo apt update
sudo apt-get update
sudo apt upgrade -y

# Install necessary tools
sudo apt install git curl unzip tar make sudo vim wget -y

# Clone your repository
git clone "Your-Repository"

# Install Python and dependencies
sudo apt install python3-pip
pip3 install -r requirements.txt

# Run the Streamlit app
python3 -m streamlit run app.py

# (Optional) Run in the background using nohup
nohup python3 -m streamlit run app.py &
