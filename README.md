# اپلیکیشن رسمی آکادمی جام‌آوران (نسخه Release امضاشده)

## ۱. بیلد خودکار نسخه اصلی (Release Signed APK) با GitHub Actions
1. محتویات این پوشه را در یک ریپازیتوری GitHub آپلود کنید.
2. وارد تب **Actions** شوید؛ بیلد نسخه اصلی به‌صورت خودکار انجام می‌شود.
3. از بخش **Artifacts** فایل **`app-release-signed-apk`** (نسخه نهایی و اصلی بدون دیباگ) را دانلود و نصب کنید.

## ۲. بیلد در Android Studio
پوشه پروژه را باز کنید و از منوی **Build → Generate Signed Bundle / APK** یا با اجرای دستور زیر، نسخه نهایی امضاشده را تحویل بگیرید:
    gradle assembleRelease

## ۳. پوش نوتیفیکیشن فایربیس
فایل `google-services.json` را از کنسول فایربیس (همنام با Package Name همین برنامه: `my.app.jamavaran`) داخل پوشه `app/` قرار دهید.