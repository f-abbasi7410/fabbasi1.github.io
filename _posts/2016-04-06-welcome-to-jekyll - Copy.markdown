---
layout: post
title:  "نصب و راه اندازی jdk"
date:   2016-04-06 09:30:50 +0430
categories: jekyll update
---


<div class="xpost-new"><div class="hid">
<font face="verdana,tahoma,arial,helvetica,sans-serif">
<font>
</font></font><div style="text-align: justify;"><font size="3" face="verdana,tahoma,arial,helvetica,sans-serif">&nbsp;در این قسمت یاد خواهید گرفت که چگونه می توانید برنامه هایی که به زبان جاوا نوشته اید را روی کامپیوترتان اجرا کنید.</font><font size="3" face="verdana,tahoma,arial,helvetica,sans-serif">نگران نباشید، این فقط یک پیش نیاز است و به زودی یاد خواهید گرفت که چگونه شروع به نوشتن برنامه های ساده کنید. </font><font face="verdana,tahoma,arial,helvetica,sans-serif"><br><font size="3">
فارغ از سیستم عاملی که روی کامپیوترتان دارید، شما برای کامپایل و اجرای  
 برنامه های جاوا به ابزاری به نام JDK نیاز دارید. JDK مخفف عبارت Java   
software Development Kit است و شامل ابزارهای مورد نیاز شما برای اجرای   
برنامه های جاوا می شود. این مجموعه شامل ابزاری به نام JVM یا Java   
Virtual Machine است که ماشین مجازی جاوا نام دارد و وظیفه ی کامپایل و   
اجرای کدهای شما را برعهده دارد. خود JVM هم شامل ابزارهای دیگری است. مثلا
   javac یا java compiler اختصاصاً وظیفه ی کامپایل کردن برنامه ها را   
برعهده دارد.</font><font size="3">JDK را باید دانلود کرده و نصب کنید، می توانید برای دانلود آن به آدرس زیر مراجعه کنید.<br><font size="3"><a target="_blank" href="http://www.oracle.com/technetwork/java/javase/downloads/index.html">Java SE Downloads</a></font></font><font size="3"><br>در حال حاضر جدیدترین JDK جاوا نسخه ی 7 است. البته از 
آنجایی که اوراکل به   ما لطف داشته، JDK را هم برای ما تحریم کرده و برای 
دسترسی به اون باید  از  همون روش هایی که خودتون بلدید استفاده کنید!<br>
خب حالا که JDK رو دارید، می خواهیم درباره ی چگونگی ایجاد و اجرای یک برنامه ی جاوا صحبت کنیم.</font> <font size="3"><br>
برای شروع باید کدهایتان را درون یک وایشگر متنی (Text Editor) بنویسید. به
   این کدها سورس کد گفته می شود. کدهایی که در ادیتو نوشتید را باید با   
پسوند java. ذخیره کنید. ادیتورهای معروف در لینوکس gedit ، vi ، emacs   
هستندو در ویندوز هم که notepad را همه می شناسید. البته ادیتورهای دیگری  
 هم در دسترس هستند، مثل ++Notepad و ادیتورهای آنلاین مثل JEdit . البته برای اینکه راحتر برنامه را نوشته و اجرا کنید از نرم افزارهایی مثل NETBeans </font>و<font size="3"> IntelliJ IDEA استفاده کنید .</font><br><font size="3">حالا نوبت کامپایل کردن کدی هست که با پسوند java. ذخیره 
کرده اید. کافیست   خط فرمان را باز کنید(در ویندوز cmd و در لینوکس bash و
 در مک هم Terminal  )  و با دستور cd به محلی بروید که فایلتان را در آنجا
 ذخیره کرده اید و   دستوری به صورت javac FileName.java بنویسید. این 
دستور اگرکدهایتان خطایی   نداشته باشند به آرامی آنها را کامپایل می کند و
 فایلی به صورت   FileName.class به عنوان خروجی می دهد. اگر هم کدتان خطا 
داشت محل خطا و   توضیحاتی برای آن نشان می دهد.<br>
<br>
توجه: اگر دستور javac  را زدید و با خطایی به صورت</font> <font size="3"><br>
javac is not recognized as an internal or external command, operable program or batch file<br>
مواجه شدید کارهایی که می گویم را انجام دهید تا javac درست کار کند.</font><font size="3"><br>ابتدا به مسیری بروید که JDK را نصب کرده اید&nbsp; ودر شاخه bin </font><font size="3">روی یکی از فایل ها راست کلیک کنید، مثلا همان فایل اولی، و بعد   properties رابزنید و مسیری که جلوی Location  می بینید را کپی کنید مثلا :<br>"D:\Program Files (x86)\Java\jdk1.6.0_20\bin"</font><font size="3"><font size="3">&nbsp;حالا روی My Computer راست کلیک کرده، Properties را باز کنید و از پنل سمت چپ این صفحه Advanced system settings را باز کنید.</font></font><font size="3"><font size="3"><font size="3">در این جا به تب Advanced روی ...Environment Variables 
کلیک کنید. در  پنجره ی  باز شده روی new بالای کلیک کنید و در کادر اول 
بنویسید Path و در  کادر  دوم هم همان مسیری که کپی کرده بودید را paste 
کنید.</font></font></font><font size="3"><font size="3"><font size="3"><font size="3">و بعد هم تمام پنجره ها را Ok کنید و حالا امتحان کنید که آیا javac درست کار می کند یا نه! قاعدتا باید درست کار کند <br>مانند تصویر زیر<br><br><br><br><img src="http://www.up.lianportal.com/images/03567905870767312431.png"></font></font> <font size="3"><br></font></font></font></font><font face="verdana,tahoma,arial,helvetica,sans-serif"><br><font size="3"><font size="3"><font size="3"><font size="3">خب بیایید در انتهای این جلسه یک جمع بندیِ کلی از کاری که انجام دادیم داشته باشیم:</font> <font size="3"><br>
<br>برنامه ای در یک ادیتور می نویسیم و آن را با پسوند java. ذخیره می کنیم. مثلا فرض کنید اسم فایل ما Welcome است.پس به صورت&nbsp; welcom.java&nbsp; ذخیره میشود</font></font></font></font></font><font size="3"><font size="3"><font size="3"><font size="3"><font size="3">بعد باید خط فرمان را باز کنیم و با دستور cd به محلی که 
فایلمان را ذخیره   کرده ایم برویم با دستور javac Welcome.java کدمان را 
کامپایل کنیم(توجه کنید که بین javac و welcom فاصله است).</font></font></font></font></font><br><font size="3"><font size="3"><font size="3"><font size="3"><font size="3"><font size="3">در ادامه تاجایی رسیدیم که یک فایل class. به دست آمد. این 
فایل class. در   واقع همان بایت کدها (byte codes) است که خودیک زبانِ 
ماشین برای ماشین   مجازی جاوا یعنی همان JVM به شمار می آیند. البته 
برخلاف زبان ماشین که   وابستگی زیادی به سخت افزار سیستم دارد، بایت کدها 
مستقل از سخت افزارند.   پس بایت کدها حمل پذیر هستند چون می توانند روی هر
 سیستمی که JVM دارد اجرا   شوند. همه ی ماشین های مجازیِ جاوا از دولایه 
تشکیل می شوند. یک لایه که   وابسته به سیستم عامل است و یک لایه هم که 
مستقل از سیستم عامل است. بایت   کدها با قسمت مستقل از سیستم عامل کار 
دارند که روی همه ی ماشین های  مجازیِ  جاوا ساختار یکسانی دارد ولی قسمت 
وابسته به سیستم عامل مختص همان  سیستم  عامل است و چون کدهای ما به این 
قسمت کاری ندارند پس متفاوت بودن  این لایه  در سیستم عامل ها مشکلی در حمل
 پذیر بودن برنامه های جاوا ایجاد  نمی کند.  از این توضیحات که بگذریم </font></font></font></font></font></font><font size="3"><font size="3"><font size="3"><font size="3"><font size="3"><font size="3"><font size="3">فایل Welcome.class به دست آمده را با دستور java Welcome اجرا کنیم. <br><br><img src="http://www.up.lianportal.com/images/31521678324871630521.png"></font>&nbsp;<font size="3"><br></font></font></font> <font size="3"><br></font></font></font></font></font><br><font size="3">و در این جا هم خروجیِ برنامه ی ما نشان داده می شود.                 </font> <font size="3"><br><br><br><img src="http://www.up.lianportal.com/images/58831939220731532097.png"></font><h2 class="title icon" style="text-align: justify;"><font size="3" face="verdana,tahoma,arial,helvetica,sans-serif">امیدوارم که خوب موضوع را گرفته باشین</font></h2><h2 class="title icon" style="text-align: justify;"><br></h2></div><p style="text-align: justify;">

</p><font face="verdana,tahoma,arial,helvetica,sans-serif">

</font><font face="verdana,tahoma,arial,helvetica,sans-serif">
</font>
<br>برچسب‌ها: <a href="/tag/jdk">jdk</a>, <a href="/tag/%d9%86%d8%b5%d8%a8-jdk">نصب jdk</a>, <a href="/tag/%d9%86%d8%ad%d9%88%d9%87-%d9%82%d8%b1%d8%a7%d8%b1-%d8%af%d8%a7%d8%af%d9%86-%d9%85%d8%b3%db%8c%d8%b1-%d8%b4%d8%a7%d8%ae%d9%87-bin-%d8%af%d8%b1-%d9%85%d8%aa%d8%ba%db%8c%db%8c%d8%b1-%d8%b3%db%8c%d8%b3%d8%aa%d9%85%db%8c-pat">نحوه قرار دادن مسیر شاخه bin  در متغییر سیستمی pat</a>, <a href="/tag/path">path</a><br><br>
</div></div>



