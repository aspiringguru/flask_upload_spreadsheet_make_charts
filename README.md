# flask file upload demos   

simple demo of file uploading with flask.  

### Setup  

reusing virtual env from previous setup.
python3 -m venv demo2.peerbanking.com.au_env

unix
source demo2.peerbanking.com.au_env/bin/activate
windows
demo2.peerbanking.com.au_env\Scripts\activate

checking existing packages installed.
---------------------------
$ pip freeze
click==8.1.3
Flask==2.1.2
gunicorn==20.1.0
importlib-metadata==4.12.0
itsdangerous==2.1.2
Jinja2==3.1.2
MarkupSafe==2.1.1
Werkzeug==2.1.2
zipp==3.8.0
---------------------------

install packages as required for this project.
pip install Flask  (already installed.)
pip install Flask-Reuploaded
pip install pandas   
pip install openpyxl
pip install matplotlib
pip install UliPlot
pip install Flask-WTF

python server.py  
