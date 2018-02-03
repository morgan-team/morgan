# morgantm

سورس ورژن 1 مورگان روی گیت قرار گرفت


اول از همه سورس را از حالت زیپ در اورید :

unzip Morgan.zip

 سپس سورس را کلون میکنیم :
 
git clone https://github.com/morgan-team/morgantm

 وارد مسیر زیر میشویم**
 
Morgan/api/bot/bot.lua

 در خط 3 توکن برات ای پی را وارد می کنیم
 
 در خط 5 ایدی عددی سودو یعنی ایدی خود را وارد می کنیم 
 
 در خط 165ایدی سودو اصلی یعنی خودتون و ایدی سی ال ای  یعنی ایدی رباتتون رو قرار میدید. 
 
یو میکنیم‌ خارج میشیم‌ ....
 
وارد مسیر زیر میشیم

Morgan/cli/plugins/Tools

در خط [2] ایدی عددی سودو قرار میدهید .

سیو میکنم‌ خارج میشیم‌....

سپس وارد مسیر زیر میشویم 

Morgan/cli/bot/bot.lua

در خط 17 ایدی عددی ربات ای پی را وارد می کنیم 

در خط 95 ایدی خودتون و ایدی سی ال ای را جایگزین می کنید

سیو میکنم‌ خارج میشیم‌....

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

