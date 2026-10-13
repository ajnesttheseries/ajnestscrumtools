# Agile & Scrum Transformation

ชุดแอนิเมชันประกอบการอบรม Agile & Scrum โดย **Aj. NesT the Series**

หน้าแรก (`index.html`) รวมแอนิเมชันทั้ง 7 ชุด ผู้อบรมกดการ์ดเพื่อเปิดดู หรือกด "เลือกฉาก" เพื่อกระโดดไปฉากที่ต้องการได้

| ช่วง | ชุด | ไฟล์ | จำนวนฉาก |
|---|---|---|---|
| ภาพรวม | 1 · Scrum หนึ่งรอบ Sprint | `animations/01-scrum-sprint-cycle.html` | 11 |
| ภาพรวม | 2 · Scrum 20 ขั้น | `animations/02-scrum-20-steps.html` | 20 |
| ลงมือทำ | 3 · เขียนงาน | `animations/03-writing-user-stories.html` | 4 |
| ลงมือทำ | 4 · ประเมินขนาด | `animations/04-estimation.html` | 5 |
| ลงมือทำ | 5 · วางแผนและคุมรอบ | `animations/05-plan-and-control.html` | 5 |
| ลงมือทำ | 6 · ตรวจและปรับ | `animations/06-inspect-and-adapt.html` | 5 |
| มุมมองเปรียบเทียบ | 7 · เครื่องมือเทียบ | `animations/07-tools-compare.html` | 4 |

## ลิงก์ตรงไปยังชุดหรือฉาก

- `#m3` เปิดชุดที่ 3
- `#m4-s3` เปิดชุดที่ 4 ที่ฉาก 3 (เช่น `.../#m4-s3` = Planning Poker)

## คีย์ลัดระหว่างดู

`←` `→` เปลี่ยนฉาก · `Space` เล่นซ้ำ · `Esc` กลับหน้ารวม

## เผยแพร่ขึ้นเว็บ (GitHub Pages)

เว็บ deploy อัตโนมัติด้วย GitHub Actions (`.github/workflows/pages.yml`) ทุกครั้งที่ push
ถ้ายังไม่ขึ้น ให้เปิด **Settings → Pages → Build and deployment → Source: GitHub Actions** แล้วสั่งรัน workflow อีกครั้ง

## เพิ่มชุดใหม่

1. วางไฟล์ HTML ใน `animations/`
2. ใส่ภาพตัวอย่างขนาด 16:9 ใน `assets/` ชื่อเดียวกับไฟล์ (`.jpg`)
3. เพิ่มรายการใน `MODS` และ `LANES` ใน `index.html` (`sel` คือ CSS selector ของปุ่มเลือกฉากในไฟล์นั้น)
