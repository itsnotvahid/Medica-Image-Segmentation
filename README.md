# قطعه بندی کردن تصاویر پزشکی با استفاده از شبکه های عصبی عمیق

### ۱بیان مساله و چالش ها:
قطعه بندی کردن یکی از چندین روش پردازش روی تصاویر در حوزه بینایی کامپیوتر است که به دلیل استفاده های بسیار کاربردی آن تقریبا یکی از مهمترین ها  در این حوزه است
در کار به خصوص ما که (( جدا کردن و قطعه بندی کردن غذه های سرطانی که شامل سرطان روده و معده و محل قرار گیری آن ها از عضو های سالم)) در  تصویر است
هدف از این کار کاهش زمان و هزینه های مربوط به تشخیص و جداسازی قسمت های عکس هاست که به صورت انسانی انجام میشود که بسیار احتمالا خطا نیز در آن وجود دارد بعضی از خطاهای رادیولوژیست ها عبارتند از
:[اطلاعات بیشتر درباره این موضوع ](https://radiopaedia.org/articles/errors-in-diagnostic-radiology)

1.شناسایی بافت اما با تشخیص نادرست که ممکن است بخاطر عدم تجربه کافی رادیولوژیست و پیچیدگی بسیاز زیاد یا اعتماد به نفس فرد اتفاق بیوفتد

2.بخاطر خستگی یا مشکلات شخصی و موضوعاتی اینچنین 

در صورت وجود مدل های هوش مصنوعی قوی و کارآمد میتوان کمک بسیار بزرگی به بیماران و پزشکان باشد تااز زمان, هزینه و اشتباه انسانی کاسته شود

اما در این مسیر نیز چالش های خاصی وجود دارند که بعضی از آن ها عبارتند از :

 پیچیدگی تصاویر پزشکی: تصاویر پزشکی، به دلیل ماهیت خاص خود، درک و تجزیه و تحلیل آنها را دشوار می کند. تصاویر پزشکی عموماً دارای جزئیات بسیار زیادی هستند و تفاوت های کوچک در تصویر ممکن است تفاوت های معنایی بزرگی ایجاد کند. این پیچیدگی ها باعث می شود برای تقسیم یکنواخت و دقیق این عناصر سخت باشد.

 عدم وجود مدل های هوش مصنوعی و داده های کافی: در زمینه تقسیم تصویر در تصاویر پزشکی، عدم وجود مدل های هوش مصنوعی کافی یک چالش مهم است. زیرا برای آموزش یک مدل نیاز به مجموعه داده های بزرگ و برچسب دار است که بسیاری از زمینه های پزشکی کمترین دسترسی به آنها را دارند. این باعث می شود تا چالش بیشتری در تولید مدل های مناسب برای تقسیم تصویر پزشکی وجود داشته باشد.
 تفاوت های ساختاری: ساختار بدن انسان و چیدمان دقیق عناصر داخلی مانند روده های بزرگ و کوچک و معده، یک چالش راهبردی برای تقسیم تصویر پزشکی ایجاد می کند. هر فرد ممکن است تفاوت های جزئی در ساختار و شکل این عناصر داشته باشد و این باعث می شود که الگوریتم های تقطیع تصویر باید بسیار منعطف و برآمده از این تفاوت های ساختاری باشند.


### روش پیشنهادی
[U-Net: Convolutional Networks for Biomedical Image Segmentation](https://paperswithcode.com/paper/u-net-convolutional-networks-for-biomedical)



![image](https://github.com/itsnotvahid/Medica-Image-Segmentation/assets/133800357/64d3bd47-6baf-4bee-a1dc-60598b74e0fe)
