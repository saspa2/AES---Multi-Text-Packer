🇮🇷 فارسی
بستهٔ چندمتنی با AES

این پروژه یک ابزار ساده و آموزشی برای رمزنگاری چند متن مختلف با کلیدهای متفاوت و قرار دادن همهٔ آن‌ها در یک بستهٔ رمزنگاری‌شدهٔ واحد است. هر کلید فقط متن مربوط به خودش را بازیابی می‌کند و باقی رکوردها قابل تشخیص نیستند.

ویژگی‌ها

رمزنگاری با AES-GCM 256bit

هر متن با یک کلید متفاوت رمز می‌شود

وجود padding برای پنهان‌سازی تعداد واقعی پیام‌ها

امکان باز کردن بسته با هر کلید و نمایش فقط متن مربوط به همان کلید

پیاده‌سازی در یک فایل HTML با WebCrypto

نحوهٔ استفاده (خلاصه)

هر ردیف = یک متن + یک کلید

روی «تولید بستهٔ رمزنگاری‌شده» کلیک کن → یک رشتهٔ Base64 تحویل می‌دهد

رشتهٔ بسته را نگه‌داری یا ارسال کن

برای بازیابی متن، همان بسته را وارد کن و کلید مدنظر را بزن

فقط متن مربوط به آن کلید نمایش داده می‌شود

🇬🇧 English
AES Multi-Message Package

This project is a simple educational tool for encrypting multiple texts using different keys and storing all of them inside a single encrypted package. Each key can decrypt only its own message, and padding records hide the real number of messages.

Features

AES-GCM 256-bit encryption

Each message uses a separate key

Padding records to hide the real count

Decrypting with any key returns only its corresponding message

Implemented in a single HTML file using WebCrypto

How to Use (Short Version)

Each row = one message + one key

Click “Generate Encrypted Package” → you get a Base64 package

Save or send the package

To decode: paste the package + enter a key

Only the message for that key will be revealed