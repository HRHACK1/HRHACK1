apt-get update -y
apt-get upgrade -y 
cd BruteX
chmod +x *
apt-get install git -y
git clone https://github.com/HRHACK1-X/BruteX.git/
bash setup.sh
python3 brutex.py
