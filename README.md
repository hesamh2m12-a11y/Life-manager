# Goal Tree | درخت اهداف

برنامه‌ریزی اهداف به‌صورت درختی: هدف اصلی ← سالانه ← شش‌ماهه ← سه‌ماهه ← ماهانه ← هفتگی ← کار روزانه.
با تیک زدن کارهای روزانه، درصد پیشرفت همه‌ی شاخه‌های بالاتر **خودکار** پر می‌شود.

Plan goals as a tree, down to daily tasks. Checking off daily tasks automatically fills progress for every goal above.

## Features | امکانات
- فارسی/انگلیسی، حتی برای عنوان هدف‌هایی که خودت می‌نویسی (برای هر هدف دو عنوان) | Persian/English UI **and** your own goal titles
- ۵ تم رنگی | 5 themes
- ذخیره‌ی خودکار در مرورگر | Auto-save in the browser
- نمودار پیشرفت (حلقه‌های هم‌مرکز و نوار) | Animated progress rings and bars
- پشتیبان JSON (خروجی/ورودی) | JSON export/import
- قابل نصب روی گوشی (PWA) | Installable on phones
- بدون سرور، بدون وابستگی (فقط فونت Vazirmatn) | No server, no dependencies

## Run | اجرا
باز کردن `index.html` در مرورگر، یا انتشار روی GitHub Pages:
Settings ← Pages ← Deploy from a branch ← `main` / `(root)` ← Save.
آدرس: `https://USERNAME.github.io/REPO/`

## Data | داده‌ها
هر کاربر داده‌هایش را فقط روی دستگاه خودش دارد (`localStorage`) و چیزی به سرور ارسال نمی‌شود. برای انتقال بین دستگاه‌ها از Export/Import استفاده کنید.
Each user's data stays on their own device. Use Export/Import to move it.

## Files
`index.html` app · `manifest.webmanifest` + `icon.svg` PWA · `LICENSE` MIT · `.gitignore`
