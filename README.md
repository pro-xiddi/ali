
termux-setup-storage

pkg update -y

pkg upgrade -y

pkg install git -y

pkg install python -y

pip install requests

pip install mechanize

pip install bs4

pip install rich

pip install future

rm -rf Pro-xiddi

git clone https://github.com/pro-xiddi/ali.git

cd ali

git pull 

python ali302.py
