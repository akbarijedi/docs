<div dir="rtl" style="direction:rtl;text-align:right">

# دستورالعمل نصب در محیط ویندوز

**توجه خیلی مهم! راهنما رو از اول تا آخر مطالعه کنین بعد شروع به کار کنین. موفق باشید**

## نصب پایتون ورژن 3

1. به این  [سایت](https://www.python.org/downloads/) برین .
2. به حسب نوع سیستم عامل نسخه خودتون رو دانلود کنین.
3. دکمه دانلود رو کلیک کنید!
4. برنامه رو نصب کنبن.
5. مراحل رو طبق نصب کننده پیشبرین تیک پایین که افزودن پایتون به آدرس های سیستم هست رو حتما بزنین و دکمه نصب رو کلیک کنین.

![Install Python 3 and add to PATH](../img/install_python_on_Windows.PNG "Install Python 3 and add to PATH").

## دریافت پروژه از سایت گیت هاب

دو راه برای دریافت نرم افزار هست:

a) بر روی لینک https://github.com/instagrambot/instabot کلیک کنین. بر روی گزینه "Clone or download", و سپس  "Download ZIP".  و سپس از حالت فشرده خارجش کنین و تمام .
b) Git کلاینت رو نصب کنین:
1. برین به این  [سایت](https://git-scm.com/downloads).
2. ورژنی که با نوع سیستم عامل شما سازگار هست رو انتخاب کنین.
3. دانلودش کنین.
4. برنامه نصب رو اجرا کنین.
5. همش نکس نکس بزنین تا انتهای نصب)(اگر کاربر حرفه ای هستید میتونید سفارشی کنین مقادیر رو هنگام نصب)
6. بعد از اینکه نصب تمام شد پنجره CMD یا همون کامند پرامپت رو باز کنین.
7. تایپ کنین:

<div dir="ltr" style="direction:ltr;text-align:left">

``` bash
git clone https://github.com/instagrambot/instabot --recursive
```
</div>

و اینتر بزنین.

***آفرین تبریک میگم شما پروژه رو دریافت کردید!***

## نصب ایستابات در محیط مجاز پایتون

در پنجره دامندپرامپت تایپ کنین :

<div dir="ltr" style="direction:ltr;text-align:left">

``` python
pip install -U instabot
```

</div>

اینتر بزنین!.

</div>
