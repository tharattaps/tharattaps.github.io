# Portfolio: ธรัฐภรณ์ ศรีดาวเรือง

เว็บ Portfolio แบบหน้าเดียว (HTML/CSS/JS ล้วน ไม่ต้อง build) สำหรับเผยแพร่บน GitHub Pages

## โครงสร้าง

```
index.html               หน้าเว็บ + ข้อมูลทั้งหมด (แก้ในส่วน "แก้ตรงนี้")
images/homjai/           frame จาก Figma (figma-*.jpg) + หน้าเว็บที่รันจริง (live-*.png)
images/eshop/            frame จาก Figma ของ E-shop
images/bookstore/        frame จาก Figma ของ Book Store
images/flutter/          หน้าแอป Flutter
images/lab4/, images/angular-profile/, images/bootstrap-profile/   หน้าเว็บ lab ที่รันจริง
images/graphic/          งานกราฟิก
.nojekyll                ให้ GitHub Pages เสิร์ฟไฟล์ตรง ๆ
```

เพิ่มหรือเปลี่ยนรูป: วางไฟล์ในโฟลเดอร์ images/ แล้วแก้ชื่อไฟล์ในข้อมูลโปรเจกต์ใน index.html

## ดูในเครื่อง

ติดตั้งส่วนขยาย **Live Server** ใน VS Code แล้วคลิกขวา `index.html` > **Open with Live Server**

## เผยแพร่บน GitHub Pages

ลิงก์ที่ได้: **https://tharattaps.github.io**

```bash
git init
git add .
git commit -m "Portfolio"
git branch -M main
gh repo create tharattaps.github.io --public --source=. --push
```

จากนั้นเข้า GitHub > repo `tharattaps.github.io` > **Settings > Pages** > Source: `Deploy from a branch`, Branch: `main` / `(root)` > Save
รอ 1–2 นาทีแล้วเปิด https://tharattaps.github.io

อัปเดตครั้งต่อไป: `git add . && git commit -m "update" && git push`
