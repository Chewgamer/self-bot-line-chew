# self-bot-line-chew

termux-setup-storage

cd /sdcard

apt update && apt upgrade -y && apt install python -y && apt install git -y

git clone https://github.com/Grueta/P3.git

cd p3 && python -m pip install -r pip.txt && python3 p3.py

หรือจะรันคำสั่งชุดเดียว

termux-setup-storage && cd /sdcard && apt update && apt upgrade -y && apt install python -y && apt install git -y && git clone https://github.com/Grueta/P3.git && cd p3 && python -m pip install -r pip.txt && python p3.py

ครั้งต่อไปเข้าแอพ Termux ใช้คำสั่ง

cd /sdcard/p3 && python3 p3.py
