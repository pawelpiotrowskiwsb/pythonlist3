# pythonlist3
# HelloWorldFlask
Python app made with flask<br/>
Shows Hello World text on start page
<h2>Setup</h2>
<h3>1.Clone Repository</h3>
git clone https://github.com/azaz0/HelloWorldFlask.git <br/>
cd HelloWorldFlask
<h4>macOS/Linux:</h4>
python3 -m venv venv
<h4>Windows:</h4>
py -3 -m venv venv

<h3>2.Activate The enviroment</h3>
<h4>macOS/Linux:</h4>
. venv/scripts/activate
<h4>Windows:</h4>
venv/Scripts/activate

<h3>3.Install Flask</h3>
pip install Flask

<h3>4.Add Requirements</h3>
pip install -r requirements.txt

<h2>Run</h2>
<h4>macOS/Linux:</h4>
export FLASK_APP=main<br/>
flask run<br/>
<h4>Windows/CMD:</h4>
set FLASK_APP=main<br/>
<h4>Windows/Powershell:</h4>
$env:FLASK_APP = "main.py"<br/><br/>

flask run
