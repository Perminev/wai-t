```
⢠⣤⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢠⢤⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢰⢻⠀⠀⠀⠀⠀⠀
⠈⣆⢣⠀⠀⠀⠀⠀⠀⠀⠀⢀⣏⠏⠀⠀⠀⠀⠀⠀⢠⠤⡄⠀⠀⠀⠀⠀⠀⠀⠀⢈⠟⠒⠒⡄⠀⠀
⠀⠸⡜⡆⠀⠀⢠⣄⠀⠀⠀⡞⡜⠀⠀⢀⣀⣀⠀⠀⣠⢭⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⢸⠉⠉⠀⠀⠀
⠀⠀⢱⢱⠀⣠⢣⡌⢦⠀⡸⡼⠁⠀⢰⡟⢹⢸⠀⠀⡇⢯⠀⣀⣀⣀⣀⢄⡀⠀⠀⢸⢸⠀⠀⠀⠀  weatherappinterminal 2.0v
 ⠀⠀⢇⣷⣣⠃⠘⢆⠳⢱⠁⠀⠀⢸⣇⢸⢸⠀⠀⡇⢸⠀⠙⠒⠒⠂⠈⠁⠀⠀⡞⢸⠀⢀⣀⠀
 ⠀⠀⠘⣴⠃⠀⠀⠈⢧⠇⠀⠀⠀⠈⠛⠛⠫⠽⠀⠳⠋⠀⠀⠀⠀⠀⠀⠀⠀⠀⢱⡘⠒⢉⡼⠀⠀
  ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠉⠉⠀⠀⠀⠀⠀⠀
```
### How to use it?
### API-key
first you need an api-key <br />
1 Go to this website:
`
https://openweathermap.org/
` <br />
2 Create an account <br />
3 Go to 'My API keys' <br />
4 Enter your API key name and click 'Generate' <br />
5 Congatulations you have an api key! (this API key you will need later) <br />
### Windows:
`First you need to download zip or write one command in the terminal:`
```
git clone https://github.com/Perminev/wai-t
```
`Second you need to install requirements`
```
cd YOUR_PROJECT_FOLDER
pip install -r requirements.txt
```
`Next you need to run it`
```
python main.py
```
### Linux:
`Preparing for install (You can skip this if all packages are installed and updated):`
```
sudo apt update
sudo apt-get install git
sudo apt install build-essential checkinstall
cd /opt
sudo wget https://www.python.org/ftp/python/3.9.16/Python-3.9.16.tgz
tar xzf Python-3.9.16.tgz 
cd Python-3.9.16 
sudo ./configure --enable-optimizations
sudo make altinstall
sudo rm -f /opt/Python-3.9.16.tgz
sudo apt install python3-pip
```
`First you need write one command in the terminal:`
```
git clone https://github.com/Perminev/wai-t
```
`Second you need to install requirements`
```
cd mydiary-main
pip install -r requirements.txt
```
`Next you need to run it`
```
python3 main.py
```
`if first not working`
```
python main.py
```

### Termux:
`Preparing for install (You can skip this if all packages are installed and updated):`
```
pkg install git
pkg install pip
pkg upgrade
pkg update
```
`First you need write one command in the terminal:`
```
git clone https://github.com/Perminev/mydiary
```
`Second you need to install requirements`
```
cd mydiary
pip install -r requirements.txt
```
`Next you need to run it`
```
python main.py
```

###### p.s. On the python 3.10 and newer stable working not garanted and if you open diary.db do this five commands in terminal:

```
cd YOUR_PROJECT_FOLDER
python
from main import app, db
app.app_context().push()
db.create_all()
```
