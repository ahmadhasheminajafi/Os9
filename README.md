# Os9
بخش اول

chown: با این دستور میتوانیم مالکیت فایل هارا به کاربر را تغییر بدهیم 

chown -c : این تغییرات انجام شده موجود را نشان می‌دهد و درصورت نداشتن تغییر خروجی تولید نمیشود 

chown -v :این دستور تغیرات در مالکیت را نمایش می‌دهد

chown -R:ایت دستور اعمال را بصورت بازگشتی روی دایرکتوری ها انجام می‌دهد

gpasswd : با این دستور مدیرها، کاربران و پسوردهای گروه را تعریف کرده و مدیرها میتوانند کاربران و پسوردها رو تغییر دهند.

gpasswd -M : با این دستور کاربران گرپه مشخص می‌شوند 

gpasswd -d :با این دستور کاربر را از گروه حذف میکنید 

gpasswd -a :با این دستور کاربر را به گروه اضافه میکنید 


بخش دوم

whoami:با این دستور نام کاربری را مشهاده میکنید 

id : با این دستور اطلاعات دیگر کاربری وارد شده رو مشاهده میکنیم

بخش سوم

sudo useradd oslab: با این دستور کاربر جدید مسیازیم 

sudo passwd oslab: با این دستور رمز کاربر را ست میکنیم 

بخش چهارم 

sudo groupadd sadjad: با این دستور گروه سجاد رو می‌سازیم

sudo groupadd Uni: با این دستور گروه یونی رو می‌سازیم

sudo usermod -G sadjad,Uni oslab: یا این دستور کاربر ساخته شده را به گروه ها اضافه میکنیم

sudo gpasswd -A oslab sadjad: با این دستور کاربر رو ادمین گروه سجاد میکنیم
 
بخش پنجم 

sudo useradd os2: با این دستور کاربر جدید را می‌سازیم

sudo usermod -G sadjad os2: با این دستور کاربر را به گروه سجاد اضافه میکنیم 

sudo userdel os2: با این دستور کاربر را حذف میکنیم از گروه



