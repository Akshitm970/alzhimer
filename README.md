Update the package list:
sudo apt update


Install Python and pip:
sudo apt install python3 python3-pip -y


Install Git:
sudo apt install git -y


Install Virtual Environment:
sudo apt install python3-venv -y


Clone Your GitHub Repository
git clone https://github.com/Akshitm970/alzhimer.git
cd alzhimer


Create and activate a virtual environment:
python3 -m venv venv
source venv/bin/activate



Install the dependencies from your requirements.txt file
pip install -r requirements.txt



streamlit run app2.py --server.port 8501 --server.enableCORS false
http://your-ec2-public-ip:8501


nohup streamlit run app2.py

to stop 
ps aux | grep streamlit
kill -9 <PID>
//change <PID> with id

