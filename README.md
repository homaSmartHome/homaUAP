# Homa

Homa is a lightweight smart-home panel for local HDL / iLife bus control. This repository publishes **Windows installer builds only**. It does not contain application source code.

هما یک پنل خانه هوشمند سبک برای کنترل محلی باس HDL / iLife است. این مخزن **فقط فایل‌های نصب ویندوز** را منتشر می‌کند و سورس برنامه را شامل نمی‌شود.

## Download / دانلود

**Latest Windows x64 installer:** [Releases](https://github.com/homaSmartHome/homaUAP/releases/latest)

Current release: **[v1.1.0](https://github.com/homaSmartHome/homaUAP/releases/tag/v1.1.0)**

| File | Description |
| --- | --- |
| `Homa-1.1.0-windows-x64.exe` | Setup package (English / Persian UI) |
| `SHA256SUMS.txt` | Checksum for the installer |

نسخه فعلی: **[v1.1.0](https://github.com/homaSmartHome/homaUAP/releases/tag/v1.1.0)**

| فایل | توضیح |
| --- | --- |
| `Homa-1.1.0-windows-x64.exe` | بسته نصب (رابط انگلیسی / فارسی) |
| `SHA256SUMS.txt` | مجموع کنترلی نصب‌کننده |

After download, run the `.exe` and follow the setup wizard. The installer is 64-bit Windows and includes English and Persian.

پس از دانلود، فایل `.exe` را اجرا کنید و مراحل نصب را دنبال کنید. نصب‌کننده برای ویندوز ۶۴ بیتی است و زبان‌های انگلیسی و فارسی را دارد.

## In-app updates / به‌روزرسانی داخل برنامه

Installed Windows copies of Homa can check this repository for a newer installer.

- Open **Settings → Updates**
- Automatic checking is on by default
- Download and silent install stay off until you enable them
- Windows may ask for permission when a new version is installed

نسخه‌های نصب‌شده ویندوز می‌توانند همین مخزن را برای نصب‌کننده جدیدتر بررسی کنند.

- **تنظیمات ← به‌روزرسانی** را باز کنید
- بررسی خودکار به‌طور پیش‌فرض روشن است
- دانلود و نصب بی‌صدا تا وقتی خودتان فعال نکنید خاموش می‌مانند
- هنگام نصب نسخه جدید، ویندوز ممکن است اجازه بخواهد

## Verify the installer / بررسی صحت فایل

Compare the SHA-256 of the downloaded file with `SHA256SUMS.txt` from the same release.

در PowerShell:

```powershell
Get-FileHash .\Homa-1.1.0-windows-x64.exe -Algorithm SHA256
```

The digest must match the value published next to that release.

مقدار هش باید با عدد منتشرشده در همان ریلیز یکی باشد.

## Older versions / نسخه‌های قبلی

All published installers stay on the [Releases](https://github.com/homaSmartHome/homaUAP/releases) page.

تمام نصب‌کننده‌های منتشرشده در صفحه [Releases](https://github.com/homaSmartHome/homaUAP/releases) باقی می‌مانند.
