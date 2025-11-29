<div dir="rtl">
  🇮🇷 فارسی
  
بستهٔ چند‌متنی با AES

این پروژه یک ابزار ساده و آموزشی برای رمزنگاری چند متن مختلف با کلیدهای متفاوت و قرار دادن همهٔ آن‌ها در یک بستهٔ رمزنگاری‌شدهٔ واحد است. هر کلید فقط متن مربوط به خودش را بازیابی می‌کند و بقیهٔ رکوردها غیرقابل‌تشخیص هستند.

✨ ویژگی‌ها

رمزنگاری با AES-GCM 256bit

هر متن با یک کلید جداگانه رمز می‌شود

وجود padding برای پنهان کردن تعداد واقعی پیام‌ها

امکان باز کردن بسته با هر کلید و مشاهده فقط پیام مرتبط با همان کلید

پیاده‌سازی کامل در یک فایل HTML با WebCrypto API

🚀 نحوهٔ استفاده

هر ردیف شامل یک متن + کلید است

روی «تولید بستهٔ رمزنگاری‌شده» کلیک کن → خروجی یک رشتهٔ Base64 است

این رشته را ذخیره کن یا برای کسی بفرست

برای بازیابی یک پیام: بسته را وارد کن + همان کلید را بزن

فقط پیام مرتبط با آن کلید نمایش داده می‌شود

⚠️ نسخهٔ آنلاین

آدرس اجرای آنلاین:
https://saspa2.github.io/AES---Multi-Text-Packer/AES-Multi-Message-Packer.html

اما توجه داشته باش:
استفاده از نسخهٔ آنلاین ممکن است باعث لو رفتن کلیدها و داده‌ها شود (به‌خاطر اتصال اینترنت یا افزونه‌ها / بدافزارهای احتمالی مرورگر).

پیشنهاد توصیه‌شده:
فایل AES-Multi-Message-Packer.html را دانلود کن و آن را آفلاین روی یک سیستم امن و بدون اینترنت اجرا کن.

</div>
🇬🇧 English
AES Multi-Message Package

This project is a simple educational tool for encrypting multiple independent texts using different keys and bundling all of them into a single encrypted package.
Each key can decrypt only its own message, while all other records remain indistinguishable due to padding.

✨ Features

AES-GCM 256-bit encryption

Each message is encrypted using a separate key

Padding records hide the real number of messages

Decrypting with any key reveals only the message associated with that key

Fully implemented in a single HTML file using the WebCrypto API

🚀 How to Use

Each row contains one message + one key

Click “Generate Encrypted Package” → you receive a Base64-encoded package

Store or send that package

To decrypt: paste the package and enter a key

Only the message associated with that key will be shown

⚠️ Online Version

Online demo:
https://saspa2.github.io/AES---Multi-Text-Packer/AES-Multi-Message-Packer.html

⚠️ Keep in mind:
Using the online version may expose your keys or data (due to internet-connected environments, extensions, or compromised browsers).

Recommended:
Download AES-Multi-Message-Packer.html and run it offline on a secure system.


