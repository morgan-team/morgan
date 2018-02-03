# morgantm

سورس ورژن 1 مورگان روی گیت قرار گرفت:

ابتدا پیش نیاز های سورس نصب میکنیم‌ :

 sudo apt-get update; sudo apt-get upgrade; sudo apt-get install tmux; sudo apt-get install luarocks; sudo apt-get install screen; sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev; sudo apt-get update; sudo apt-get install; sudo apt-get install upstart-sysv

 wget http://luarocks.org/releases/luarocks-2.2.2.tar.gz;tar zxpf luarocks-2.2.2.tar.gz;cd luarocks-2.2.2 && ./configure; sudo make bootstrap;sudo luarocks install luasocket;sudo luarocks install luasec;sudo luarocks install redis-lua;sudo luarocks install lua-term;sudo luarocks install serpent;sudo luarocks install dkjson;sudo luarocks install lanes;sudo luarocks install Lua-cURL

بزنید :
 cd
======================
 سپس سورس را کلون میکنیم :
git clone https://github.com/morgan-team/morgantm
======================
 وارد مسیر زیر میشویم**
Morgan/api/bot/bot.lua
در خط [3] توکن ربات (api) که مرحله سوم با شماره ربات ساخیم وارد میکنیم.
در خط [5] ایدی سودو اصلی یعنی خودتون قرار میدید .
در خط [165] ایدی سودو اصلی یعنی خودتون و ایدی ربات cli ینی ایدی تلگرام رباتتون رو قرار میدید . اگر سه تا عدد پیشفرض نوشته بود مال خودتونو جاگزین کنید سومی رو پاک کنید .
سیو میکنیم‌ خارج میشیم‌ ....
======================
 وارد مسیر زیر میشیم‌
Morgan/cli/plugins/Tools
در خط [2] ایدی عددی سودو قرار میدهید .
سیو میکنم‌ خارج میشیم‌....
سپس وارد مسیر زیر میشویم 
Morgan/cli/bot/bot.lua
و بعد در خط [17] ایدی ربات (api) را وارد میکنیم توجه داشته باشید ایدی عددی ربات (api) اول توکن نوشته شده است .
در خط 95 دوتا ایدی پیشفرض نوشته شما ایدی خودتون و ایدی ربات cli رو باهاش جایگزین کنید .
سیو میکنم‌ خارج میشیم‌....
======================
 دستورات زیر در ترمینال وارد کنید ...
cd Morgan/cli

chmod +x Morgan.sh

chmod 777 auto.sh && sed -i -e 's/\r$//' auto.sh

./Morgan.sh install 

 ./Morgan.sh

صبر میکنیم تا کامل نصب بشه 

شماره ربات وارد مکنید کد میزنید‌
از سرور خارج و دوباره وصل میشید...
کد های زیر را در سرور میزنیم 
cd Morgan/api

chmod +x Morgan.sh

chmod 777 auto.sh && sed -i -e 's/\r$//' auto.sh
./Morgan.sh install
./Morgan.sh
صبر کنید تموم شه ، بعد ترمینال رو ببندید .


حالا ربات اماده لانچ کردنه :
cd Morgan/api && chmod +x auto.sh && chmod 777 auto.sh && screen ./auto.sh

یه ترمینال دیگه باز کنید و این رو بزنید : 
cd Morgan/cli && chmod +x auto.sh && chmod 777 auto.sh && screen ./auto.sh 

تموم . میتونید از سرور خارج شید .

▪️Channel : @morgan_team
▪️Edited By : @sheikh_mamad
====================
