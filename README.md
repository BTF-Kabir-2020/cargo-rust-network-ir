# Cargo & Rust Network Access Test

Project page: https://ghourchiani.ir/projects/cargo-rust-network-ir

---

## 🇮🇷 بررسی دسترسی Cargo و Rust در ایران

در ایران، دسترسی به برخی منابع مرتبط با زبان Rust و ابزار Cargo ممکن است در بعضی شبکه‌ها
با اختلال، تأخیر یا نیاز به تونل‌سازی خارجی همراه باشد که این موضوع می‌تواند فرآیند توسعه را
کند یا متوقف کند.

### تجربه دسترسی شبکه

در بررسی فنی مشاهده شد که با استفاده از برخی **DNSهای جایگزین (به صورت IP)**، امکان دسترسی مستقیم
به مخازن Cargo و Rust در بعضی شبکه‌ها فراهم شد و دریافت پکیج‌ها بدون خطای اتصال انجام گرفت.

DNSهای تست شده:
- `178.22.122.100`
- `185.51.200.2`

بدیهی است که نتیجه این روش به عوامل مختلفی از جمله:
- ارائه‌دهنده اینترنت (ISP)
- موقعیت جغرافیایی
- سیاست‌های شبکه
- تنظیمات سیستم کاربر

وابسته است و ممکن است برای همه کاربران یکسان نباشد.

این مخزن صرفاً جهت ثبت یک تجربه فنی و بررسی رفتار شبکه‌ای Cargo منتشر شده و
جنبه معرفی، تبلیغ یا توصیه سرویس یا ابزار خاصی ندارد.

---

## 🌍 English Description

In some regions, accessing Rust-related resources and Cargo registries may be
affected by network restrictions, instability, or routing limitations, which can
slow down or block the development workflow.

### Network Access Experience

During technical testing, it was observed that using certain **alternative DNS servers (IP only)**
enabled direct access to Cargo and Rust registries in some network environments,
allowing packages to be fetched without connection errors.

Tested DNS IPs:
- `178.22.122.100`
- `185.51.200.2`

The effectiveness of this approach depends on several factors, including:
- Internet Service Provider (ISP)
- Geographic location
- Network policies
- Local system configuration

Results may vary between users and networks.

This repository is published solely to document a technical observation and
network behavior analysis of Cargo, and does not promote or endorse any specific
service or configuration.

---

## ⚙️ Test Environment

- Rust: stable
- Cargo: latest
- Network: local / restricted
  
