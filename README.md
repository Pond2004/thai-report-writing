# thai-report-writing

Claude skill สำหรับเขียน แก้ และตรวจรายงานภาษาไทย ให้อ่านเป็นธรรมชาติแบบคนไทยเขียน และส่งออกเป็น .docx ภาษาไทยที่ Word แสดงผลถูก

รายละเอียดการทำงานอยู่ใน [SKILL.md](SKILL.md)

## ติดตั้ง

**Claude Code** — clone ลงโฟลเดอร์สกิลของผู้ใช้

```sh
git clone <url ของ repo นี้> ~/.claude/skills/thai-report-writing
```

**claude.ai** — ดาวน์โหลด repo เป็น zip แล้วอัปโหลดที่ Settings → Capabilities → Skills

ตัวสร้าง .docx ต้องใช้ Python 3.11+ หรือ Node.js อย่างใดอย่างหนึ่ง ไม่ต้องติดตั้งแพ็กเกจเพิ่ม

## ที่มาและสัญญาอนุญาต

รวมจากสามโครงการที่ใช้ MIT License ไฟล์ LICENSE ของแต่ละโครงการอยู่ในโฟลเดอร์ที่เกี่ยวข้อง

- kien-thai © 2026 Chakrit Wichian — `references/thai-prose/`
- technical-writing-density © 2026 Michael Welles — `references/technical-density.md`
- thai-docx © 2026 Sayam Sriphua — `thai-docx/`
