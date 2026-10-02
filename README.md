```bash
pkg update -y && pkg upgrade -y
pkg install -y python git
pip install requests
termux-setup-storage

git clone https://github.com/cadetrooh/roohkey.git
cd roohkey
python3 rooh.py
```
