# micropython

http://swf.com.tw/files/microPython/DAY1_ppt.zip
http://swf.com.tw/files/microPython/tool.zip
https://www.arduined.eu/ch340g-converter-windows-7-driver-download/
http://swf.com.tw/files/microPython/DAY1_code.zip

d0 g16
d5 g14
d6 g12
d7 g13
d8 g15
tx g01
rx g03
d1 g05
d2 g04
d3 g00
d4 g02

python.org download python3.7 64bit version
pip install esptool 燒錄套件
32bit 40Hz DIO 32Mbit com3 115200
putty link 115200 com3  ctrl+d==>reboot
in putty micropython
ctrl+e==>edit, ctrl+d==>finish edit, ctrl+c==> stop

vscode Python-autopep8 autoedit puthon3.7

硬體套件 hardware module
https://www.wemos.cc/
https://wiki.wemos.cc/products:d1:d1_mini
https://wiki.wemos.cc/products:d1_mini_shields:battery_shield

https://wiki.wemos.cc/products:d1_mini_shields:rgb_led_shield
https://wiki.wemos.cc/products:d1_mini_shields:tft_2.4_shield


upload python code
pip install adafruit-ampy
ampy --help
ampy --port com3 ls
ampy --port com3 get boot.py
ampy --port com3 put boot.py #upload python code

https://thingspeak.com
https://api.thingspeak.com/update?api_key=IBHMIUXT3NO2V6B3&field1=24.6

http://docs.micropython.org/en/latest/library/index.html

scl clock Pin(5)
sda data  Pin(4)

LCDAssistant.exe 將圖檔轉成數值資料
Vertical
Little
圖檔

bytes('你好',encoding='utf-8')  #中文編碼成 byte資料 

10.0.1.147 esp8622 web server

bluestacks android 模擬器

pip flask #search flask module
https://pypi.org/project/Flask/  所有py的套件說明

建立虛擬環境
python -m venv env 建立虛擬環境
env\Scripts\activate 啟用虛擬環境
pip install flask 安裝FLASK
python -m pip install --upgrade pip 更新PIP

use vscode folder open web folder
env 須在工作環 env

static web
templates web
DEBUG 模式下 可在網頁上點選輸入code 進入termal js 模式

ngrok 可跳過防火
ngrok http 80

pip freeze > requiremnet.txt 套件例表
pip install -r requiremnet.txt 重安裝套件

line chatbot 
pip install line-bot-sdk  #install line module
https://developers.line.biz #login in
https://developers.line.biz/console/
Channel secret 

Channel access token (long-lived) 

heroku.com
create ben0955line
Install the Heroku CLI https://devcenter.heroku.com/articles/heroku-cli
heroku download heroku-x64.exe
keyin'heroku login'

git download
https://git-scm.com/
install Git-2.21.0-64-bit.exe
git config --global user.email "cochu55@gmail.com"
git config --global user.name "ben0955"

git init 

soure 下必要檔案
Procfile #啟動檔
runtime.txt #python 指定版本
requiremnet.txt #加入 gunicorn

git add . #複制檔案

git commit -am "line chatbot v1.0.0" #註解

heroku git:remote -a ben0955line  #帳號設定
git push heroku master
heroku open

https://dashboard.heroku.com/apps/ben0955line/log



Auto-reply messages: disable
Use webhooks: Enabled


https://ben0955line.herokuapp.com/btn?key=zzzzz&id=wash_dish  #主發訊息

ampy --port com3 put main.py #esp 自動執行
ampy --port com3 rm main.py #移除






