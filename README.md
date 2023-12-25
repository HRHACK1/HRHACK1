apt-get update -y
apt-get upgrade -y 
apt-get install git -y
git clone https://github.com/MrHacker-X/BruteX.git/
cd BruteX
chmod +x *
bash setup.sh
python3 brutex.py
