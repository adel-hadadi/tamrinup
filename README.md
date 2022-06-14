# tamrinup
فرانت اند وب سایت شبیه به فرادرس

وبسایت تمریناپ به منظور فروش دوره های آموزشی در حوزه های مختلف کاری توسط اساتید مجرب آن حوزه طراحی شده است. لازم به ذکر است که این وبسایت با استفاده از 
کتابخانه bootstrap  برای device ها مختلف از جمله دسکتاپ، تبلت و موبایل کاملا ریسپانسیو طراحی شده است.

pages: 

index: 
در ابتدای این صفحه سکشنی برای جستوجو بین هزاران قرار دارد و در پایین این سکشن بخشی برای نمایش آمار کلی وبسایت به کار وجود دارد. در بخش پایین تر موضوعات مختلف 
آموزشی موجود میباشید تا کاربر راحت تر به آموزش مورد نظر خود دسترسی داشته باشد.
در قسمت پایین تر دوره های آموزشی محبوب، رایگان، جدیدترین و ... وجود دارد که هرکدام از آموزش ها با استفاده از کلاس کارد بوتسرترپ پیاده سازی شده است. همچنین این 
کارد ها قابلیت اسکرل کردن دارند که با کشیدن کارت ها به چپ یا راست جای آن ها تغییر میکند. این قابلیت با استفاده از کتاب خانه owl-corusel پیاده سازی شده است. این 
کتاب خانه از Jquery که یکی از کتابخانه های محبوب javascript است استفاده میکند. همچنین این سکشن کاملن reasponsive میباشد و در صفحات کوچکتر تعداد کمتری از آموزش ها
را نمایش میدهد.

در قسمت پایین تر این سکشن، بخشی برای نمایش نقشه راه ها و همچنین اطلاعات کلی درباره هرکدام از هرکدام از این بخش ها طراحی شده است.

در قسمت های پایینی سکشنی برای همکاری اساتید با وبسایت تمریناپ طراحی شده است و در پایان صفحه footer وبسایت قرار دارد.

course: 

در این صفحه اطلاعات تکمیلی آموزش را به کاربر نمایش میدهد. این اطلاعات شامل مدرس دوره، درباره دوره، لیست سرفصل ها، قسمت های آموزشی که با کلیک بر روی هرکدام
از قسمت ها ویدیو آن قسمت بعلاوه توضیحات آن قسمت نمایش داده میشود. برای نمایش زیبا تر ویدیو های از کتابخانه video.js استفاده شده که قابلیت های زیادی به کاربر
نمایش میدهد. سکشن سمت چپ که شامل اطلاعاتی از جمله قیمت دوره (در صورت داشتن تخفیف قیمت اصلی و همچنین قیمت تخفیف بعلاوه تاریخ انقضا تخفیف) و ... میباشد در هنگام 
اسکرول به پایین در بالا صفحه میماند تا به قسمت footer وبسایت برسید که این قابلیت با استفاده از کتابخانه sticky-sidebar.js  پیاده سازی شده است. و در پایان این 
صفحه نظرات دانشجویان ،تگ های آموزش و ... موجود میباشد.

how-to-learn: 
این صفحه به منظور نمایش نقشه راه هر حوزه استفاده میشود در ابتدای این صفحه اطلاعات نقشه راه موجود میباشد و سپس لیست هر قدم از آموزش ها موجود میباشد که با کلیک 
بر روی هر کدام از آموزش ها به صفحه آن مربوط به آن آموزش انتقال داده میشوید. 

 teacher-panel:
این صفحه به منظور استفاده مدرسان برای مدیریت حساب، آموزش ها و مدیریت حساب بانکی خود طراحی شده است که در صفحات جدا از هم قرار دارند و با کلیک بر روی هر کدام 
از تب های میتوان صفحه پایین را به صورت single page action تغیر داد. در بالای این صفحه اطلاعات استاد نمایش داده میشود.

assets folder: 
css: 
این فولدر شامل یک فایل css میباشد که شامل استایل های کلی وبسایت میباشد.

fonts: 
در این پوشه فایل های مربوط به فونت شبنم قرار دارد.
images: 
شامل تمام تصاویر استفاده شده در وبسایت میباشد.

js: 
این پوشه شامل فایل های جاوااسکریپتی بوتسرپ، jquery.js که شامل کد های کتابخانه jquery است و grid.js که کد های کلی جهت مدیرت اکشن های وبسایت است استفاده میشود، میباشد.

owl-carouse: 
این پوشه شامل کد های جاوااسکریپت و css کتابخانه owl-carousel میباشد که برای درست کردن سکشن ها با قابلیت drag and drop برای اسکرول کارد ها استفاده شده است.

select2: 
فایل های مورد نیاز کتابخانه select 2 در این پوشه موجود میباشد. از این کتابخانه به منظور ساخت select input ها با قابلیت multiple selection استفاده میشود. قابل
ذکر است که این کتابخانه از jquery.js استفاده میکند.

sticky-sidebar:
این فایل شامل کد های javascript به منظور handle چسبندگی سایدبار به صفحه استفاده میشود.

