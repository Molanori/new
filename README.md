# اپ اندروید وحوش+ (WebView)

## قدم ۱ — ساخت ریپو در گیت‌هاب
1. وارد github.com شو
2. دکمه `New repository` → اسم: `vahoush-app` → گزینه Public یا Private (هر دو برای بیلد اوکیه)
3. تیک `Add a README file` را **نزن** → `Create repository`

## قدم ۲ — آپلود فایل‌ها
1. در صفحه ریپو روی `uploading an existing file` کلیک کن
2. **محتویات داخل** پوشه `VahoushApp` (نه خود پوشه) را با موس بکش و رها کن داخل صفحه
   - باید این‌ها دیده شوند: `app/` ،`.github/` ،`settings.gradle` ،`build.gradle`
   - نکته: پوشه `.github` مخفیه؛ موقع انتخاب فایل‌ها مطمئن شو که انتخاب شده
3. پایین صفحه `Commit changes` را بزن

## قدم ۳ — بیلد APK
1. تب `Actions` را باز کن (اگه خواست `Enable workflows` را بزن)
2. از لیست سمت چپ `Build APK` → دکمه `Run workflow` (یا صبر کن خودش با پوش اجرا بشه)
3. ۵ تا ۱۰ دقیقه صبر کن تا تیک سبز بخوره
4. وارد آن ران شو → پایین صفحه بخش `Artifacts` → فایل `vahoush-apk` را دانلود کن
5. فایل زیپ را باز کن؛ داخلش `app-debug.apk` است

## قدم ۴ — نصب روی گوشی
1. `app-debug.apk` را به گوشی منتقل کن و بازش کن
2. اجازه `Install unknown apps` را به برنامه‌ای که باهاش باز کردی (Chrome یا Files) بده
3. `Install` را بزن (اگه Play Protect هشدار داد `Install anyway`)

## آپدیت بعدی
- `versionCode` را در `app/build.gradle` یکی زیاد کن، کامیت بزن، دوباره از Artifacts دانلود کن
