# streamlit-python
In this repository, I try to deploy a streamlit app that represent titanic prediction. The prediction is done by xgboost and  based on input field, it's predict if the passenger will survived or not!
Then I deploy this project to AWS EC2 Instances.
For deploy to AWS EC2, you have to follow this steps one by one: 
1- Make your EC2 instance in your AWS account.
2- Run this commands one-by-one:
a)sudo apt update
b)sudo apt-get update
c)sudo apt upgrade -y
d)sudo apt install git curl unzip tar make sudo vim wget -y
e)git clone "Your-repository"
f)sudo apt install python3-pip
g)pip3 install -r requirements.txt
h)python3 -m streamlit run app.py
i)nohup python3 -m streamlit run app.py
