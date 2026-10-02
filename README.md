
pkg update -y && pkg upgrade -y
pkg install -y python git
pip install requests
termux-setup-storage
apt install git

git clone https://github.com/<you>/rooh.git
cd rooh
python rooh.py
