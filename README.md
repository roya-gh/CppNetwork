# CppNetwork
GameNetworkingSockets test exe files.

‫‫برای کامپایل برنامه ابتدا dependency ها را به ترتیب زیر کامپایل/ نصب کردم:
باینریهای‫ openssl را از لینک https://slproweb.com/products/Win32OpenSSL.html دریافت کرده نصب ‫کردم ( به دلیل دشوار بودن کامپایل openssl در ویندوز من همیشه در پروژه ها باینری آن را نصب میکنم)
‫‫از رپوزیتوری اشاره شده در لینک‌های کتابخانه protobuf  را دریافت کرده و به وسیله cmake  پروژه msvc 2017 ‫نسخه 64 بیتی release آن را make کرده سپس با استفاده از visual studio آن را build  کردم.
‫سپس کد کتابخانه را گرفته و با cmake پروژه msvc 2017 نسخه 64  بیتی release آن را make کرده و با visual studio آن را build  کردم. Dll های ساخته شده را در کنار فایلهای اجرایی تست قرار دادم. 
