# แผนผังไฟล์โครงการ

เริ่มอ่านภาพรวมและบทบาทของผู้จัดทำที่ [README](../README.md)

| โฟลเดอร์ | เนื้อหา |
| --- | --- |
| `diagrams/` | ไฟล์ draw.io ที่แก้ไขได้: EER, Relational Schema, 3NF และ Data Dictionary |
| `docs/reports/` | รายงานการออกแบบฐานข้อมูลและเอกสาร 3NF แบบ PDF |
| `docs/slides/` | สไลด์นำเสนอแบบ PDF |
| `assets/previews/` | ภาพตัวอย่างแผนผังสำหรับหน้า README |

## ตำแหน่งไฟล์ที่เปลี่ยน

เอกสาร PDF เดิมอาจแสดงชื่อโฟลเดอร์เก่าในเนื้อหา ตารางนี้แสดงตำแหน่งปัจจุบัน โดยลิงก์ใน PDF ได้ปรับให้ชี้ไปยังตำแหน่งใหม่แล้ว

| ตำแหน่งเดิม | ตำแหน่งปัจจุบัน |
| --- | --- |
| `docs/database-design-report.pdf` | `docs/reports/database-design-report.pdf` |
| `docs/database-design-slides.pdf` | `docs/slides/database-design-slides.pdf` |
| `docs/normalization-3nf.pdf` | `docs/reports/normalization-3nf.pdf` |
| `previews/` | `assets/previews/` |

## รายการไฟล์ทั้งหมด

รายการนี้ไม่รวม node_modules ข้อมูลระหว่างใช้งาน และไฟล์ส่วนตัว

```text
assets/
  previews/
    relational-schema.png
diagrams/
  data-dictionary.drawio
  eer-diagram.drawio
  normalization-3nf.drawio
  relational-schema.drawio
docs/
  reports/
    database-design-report.pdf
    normalization-3nf.pdf
  slides/
    database-design-slides.pdf
  STRUCTURE.md
.gitignore
README.md
```
