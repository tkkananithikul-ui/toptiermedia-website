# Top Tier Media — Website Demo

Demo เว็บไซต์ของ Top Tier Media สร้างจาก content ของ `4B Credential 2024.pdf` (4B = ชื่อเก่า → เปลี่ยนเป็น Top Tier Media ทั้งหมด)

## วิธีเปิดดู

```bash
# วิธีที่ 1: เปิดไฟล์โดยตรง (ง่ายที่สุด)
open index.html

# วิธีที่ 2: รัน local server (recommended สำหรับ smooth scroll)
python3 -m http.server 8000
# แล้วเปิด http://localhost:8000
```

## โครงสร้าง 9 Sections

1. **Hero** — "We Connect Your Brand to Consumers" + tagline ภาษาไทย
2. **Trust Bar** — 500+ Brands · 3,000+ Campaigns · 10+ Years · 6 Pillars
3. **Who We Are** — Get to know us + Logo card + Floating badges (TikTok Partner, 500+ Brands)
4. **Our Solutions** — 6 service pillars (Strategy / Creative / Marketplace / Media / Influencer / PR)
5. **Channels We Master** — Meta, Google, **TikTok (Exclusive Partner)**, LINE, Shopee, Lazada
6. **Funnel Approach** — Upper → Mid → Lower funnel visualization
7. **Selected Work** — 6 case study cards พร้อม metric (ROAS, Leads, Reach, PR Value)
8. **Process** — Research → Analysis → Strategy → Execute
9. **Clients** — Logo wall (marquee)
10. **Insights** — 3 blog articles preview
11. **Contact / CTA** — Email + Phone + Office info + LINE OA

## CI / Brand Colors

- **Primary Yellow:** `#FFD230` (จากโลโก้)
- **Secondary Yellow:** `#F5C419`
- **Black:** `#0A0A0A`
- **Gray (cards):** `#1A1A1A`

## Typography

- **Display (Heading):** Space Grotesk
- **Body (English):** Inter
- **Body (Thai):** Anuphan

## Tech Stack

- HTML + Tailwind CSS (CDN)
- Vanilla JS (scroll reveal, number counter, marquee)
- ไม่มี build step — เปิดไฟล์ได้เลย

## ⚠️ ข้อมูลที่ใช้ Placeholder (ต้องเปลี่ยนภายหลัง)

- [x] **Logo SVG** — มีไฟล์ `logo.svg` แล้ว (สร้างจาก SVG ให้ใกล้เคียงต้นฉบับ)
- [ ] **Logo ต้นฉบับ (PNG/SVG จริง)** — ถ้ามี ลากไฟล์ไปวางทับ `logo.svg` ในโฟลเดอร์นี้ จะแสดงผลทันที (HTML reference ที่ `logo.svg`)
- [ ] **Case studies** — ใช้ icon emoji + ชื่อทั่วไป — ควรใส่ภาพและชื่อจริงตาม approve list
- [ ] **Client logos** — ใช้ text placeholder (Client A, B, C...) — ใส่โลโก้จริงจาก credential หน้า 20-21
- [ ] **Contact email/phone** — ใช้ `contact@toptiermedia.co.th` และเบอร์เดิม `065-647-1556` — ยืนยันว่าถูกต้องไหม
- [ ] **Blog articles** — เป็นตัวอย่าง — เขียนคอนเทนต์จริงทีหลัง
- [ ] **Office address / LINE OA** — ใช้ placeholder

## Next Steps

1. ✏️ **Review demo** — เปิดดูแล้วบอกว่าชอบ/ไม่ชอบส่วนไหน อยากปรับอะไร
2. 🎨 **ใส่ asset จริง** — logo, case studies, client logos
3. 🌐 **Domain** — เลือกชื่อ + เช็คว่าว่างไหม
4. 🖥️ **Hosting** — เช็ค Hostatom support Node.js หรือต้อง Static Export
5. 🚀 **Production** — ย้ายเป็น Next.js project + deploy
