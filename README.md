```
⢠⣤⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢠⢤⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢰⢻⠀⠀⠀⠀⠀⠀
⠈⣆⢣⠀⠀⠀⠀⠀⠀⠀⠀⢀⣏⠏⠀⠀⠀⠀⠀⠀⢠⠤⡄⠀⠀⠀⠀⠀⠀⠀⠀⢈⠟⠒⠒⡄⠀⠀
⠀⠸⡜⡆⠀⠀⢠⣄⠀⠀⠀⡞⡜⠀⠀⢀⣀⣀⠀⠀⣠⢭⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⢸⠉⠉⠀⠀⠀
⠀⠀⢱⢱⠀⣠⢣⡌⢦⠀⡸⡼⠁⠀⢰⡟⢹⢸⠀⠀⡇⢯⠀⣀⣀⣀⣀⢄⡀⠀⠀⢸⢸⠀⠀⠀⠀  weatherappinterminal 2.0v
 ⠀⠀⢇⣷⣣⠃⠘⢆⠳⢱⠁⠀⠀⢸⣇⢸⢸⠀⠀⡇⢸⠀⠙⠒⠒⠂⠈⠁⠀⠀⡞⢸⠀⢀⣀⠀
 ⠀⠀⠘⣴⠃⠀⠀⠈⢧⠇⠀⠀⠀⠈⠛⠛⠫⠽⠀⠳⠋⠀⠀⠀⠀⠀⠀⠀⠀⠀⢱⡘⠒⢉⡼⠀⠀
  ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠉⠉⠀⠀⠀⠀⠀⠀
```
[RU](https://github.com/Perminev/wai-t/tree/main#%D0%BA%D0%B0%D0%BA-%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D1%8C)
[EN](https://github.com/Perminev/wai-t/tree/main#how-to-use-it)
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
cd wai-t-main
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
cd wai-t
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

### Как использовать?

### API-ключ
для начала вам нужен API-ключ <br />
1 Перейдите на этот сайт:
`
https://openweathermap.org/
` <br />
2 Создайте аккаунт <br />
3 Перейдите в каталог 'My API keys' <br />
4 Введите имя вашего API-ключа и нажмите на кнопку 'Generate' <br />
5 Поздраляем API-ключ создан! (этот API-ключ вам понадобится позже) <br />
### Windows:
`Для начала скачаете этот проект или вставте эту команду в терминал(если у вас есть git):`
```
git clone https://github.com/Perminev/wai-t
```
`Далее вам нужно установить необходимые для работы проекта библиотеки`
```
cd YOUR_PROJECT_FOLDER
pip install -r requirements.txt
```
`Далее вам нужно запустить программу через эту команду`
```
python main.py
```
### Linux:
`Подготовка к установке (Вы можете пропустить этот шаг если у вас устанолены все необхоимые компоненты):`
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
`Для начала вставте эту команду в терминал и нажмите ENTER:`
```
git clone https://github.com/Perminev/wai-t
```
`Далее вам нужно установить необходимые для работы проекта библиотеки`
```
cd wai-t-main
pip install -r requirements.txt
```
`Далее вам нужно запустить программу через эту команду`
```
python3 main.py
```
`если первая команда не работает`
```
python main.py
```

### Termux:
`Подготовка к установке (Вы можете пропустить этот шаг если у вас устанолены все необхоимые компоненты):`
```
pkg install git
pkg install pip
pkg upgrade
pkg update
```
`Для начала вставте эту команду в терминал и нажмите ENTER:`
```
git clone https://github.com/Perminev/mydiary
```
`Далее вам нужно установить необходимые для работы проекта библиотеки`
```
cd wai-t
pip install -r requirements.txt
```
`Далее вам нужно запустить программу через эту команду`
```
python main.py
```

###### p.s. На python 3.10 и новее стабильная работа не гарантируется и если вы открыли файл diary.db и у вас перестал работать код впишите эти 5 команд :

```
cd YOUR_PROJECT_FOLDER
python
from main import app, db
app.app_context().push()
db.create_all()
```
