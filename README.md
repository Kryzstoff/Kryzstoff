pkg update
pkg install git
pkg install python
pkg install python-pip
git clone https://github.com/CPMAyan/cpmayan.git
cd cpmayan
git pull
pip install -r requirements.txt
python main.py
