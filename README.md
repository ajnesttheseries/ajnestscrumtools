# Agile & Scrum Transformation

ชุดแอนิเมชันประกอบการอบรม Agile & Scrum โดย **Aj. NesT the Series**

หน้าแรก (`index.html`) รวมแอนิเมชัน 8 ชุดและ Workshop 1 ชุด ผู้อบรมกดการ์ดเพื่อเปิดดู หรือกด "เลือกฉาก" เพื่อกระโดดไปฉากที่ต้องการได้

| ลำดับบนหน้า | ช่วง | ชุด | ไฟล์ | จำนวน | ลิงก์ |
|---|---|---|---|---|---|
| 1 | ภาพรวม | Scrum หนึ่งรอบ Sprint | `animations/01-scrum-sprint-cycle.html` | 11 ฉาก | `#m1` |
| 2 | ภาพรวม | Scrum 20 ขั้น | `animations/02-scrum-20-steps.html` | 20 ฉาก | `#m2` |
| 3 | ลงมือทำ | เขียนงาน | `animations/03-writing-user-stories.html` | 4 ฉาก | `#m3` |
| 4 | ลงมือทำ | ประเมินขนาด | `animations/04-estimation.html` | 5 ฉาก | `#m4` |
| 5 | ลงมือทำ | วางแผนและคุมรอบ | `animations/05-plan-and-control.html` | 5 ฉาก | `#m5` |
| 6 | ลงมือทำ | ตรวจและปรับ | `animations/06-inspect-and-adapt.html` | 5 ฉาก | `#m6` |
| 7 | Workshop | กรอกไฟล์ Scrum ทีละช่อง | `workshop/scrum-workbook-walkthrough.html` | 20 ขั้น + Sprint 2 | `#m9` |
| 8 | มุมมองเปรียบเทียบ | เครื่องมือเทียบ | `animations/07-tools-compare.html` | 4 ฉาก | `#m7` |
| 9 | มุมมองเปรียบเทียบ | SDLC vs AIDLC | `animations/08-sdlc-vs-aidlc.html` | 18 ฉาก | `#m8` |

เลขในลิงก์ (`#m1`…`#m9`) คือตำแหน่งในรายการ `MODS` ไม่ใช่ลำดับบนหน้า จึงไม่เปลี่ยนเมื่อสลับลำดับชุด ลิงก์ที่เคยแชร์ไปแล้วยังใช้ได้

## ลิงก์ตรงไปยังชุดหรือฉาก

- `#m3` เปิดชุด "เขียนงาน"
- `#m4-s3` เปิดชุดที่ 4 ที่ฉาก 3 (เช่น `.../#m4-s3` = Planning Poker)

## คีย์ลัดระหว่างดู

`←` `→` เปลี่ยนฉาก · `Space` เล่นซ้ำ (ในชุด Workshop คือเล่นอัตโนมัติ) · `Esc` กลับหน้ารวม

## เผยแพร่ขึ้นเว็บ (GitHub Pages)

เว็บ deploy อัตโนมัติด้วย GitHub Actions (`.github/workflows/pages.yml`) ทุกครั้งที่ push
ถ้ายังไม่ขึ้น ให้เปิด **Settings → Pages → Build and deployment → Source: GitHub Actions** แล้วสั่งรัน workflow อีกครั้ง

## เพิ่มชุดใหม่

1. วางไฟล์ HTML ใน `animations/` (หรือโฟลเดอร์อื่น แล้วใส่ `dir` ในรายการ)
2. ใส่ภาพตัวอย่างขนาด 16:9 ใน `assets/` ชื่อเดียวกับไฟล์ (`.jpg`)
3. เพิ่มรายการต่อท้าย `MODS` ใน `index.html` (`sel` คือ CSS selector ของปุ่มเลือกฉากในไฟล์นั้น) แล้วใส่ตำแหน่งของรายการลงใน `LANES` ตรงช่วงที่ต้องการ
