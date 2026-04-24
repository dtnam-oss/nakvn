# NAK Logistics — Landing Page 2025

Landing page chính thức của Công ty CPTM Dịch Vụ và Vận Tải N.A.K Việt Nam (HSNL 2025).

## Stack

- HTML / CSS / Vanilla JS (single file, không build step)
- Hosting: Vercel (static)

## Local preview

```bash
python3 -m http.server 8080
# open http://localhost:8080
```

## Deploy

Auto-deploy qua Vercel khi push lên `main`. Cấu hình tại `vercel.json` (rewrite `/` → `NAK-Landing-2025.html`).

## Cấu trúc

```
.
├── NAK-Landing-2025.html   # Landing page chính
├── images/                 # Asset .webp tối ưu
├── logo-nak.png
├── vercel.json
└── README.md
```
