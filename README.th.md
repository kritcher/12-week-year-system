# ระบบปฏิบัติการ 12 Week Year

repo นี้เป็นคู่มือไม่เป็นทางการ สำหรับเอาแนวคิดจากหนังสือ *The 12 Week Year* มาทำเป็นระบบ execution ที่คนกับ AI ใช้ร่วมกันได้จริง

ไม่ใช่สรุปหนังสือแทนการอ่านต้นฉบับ และไม่เกี่ยวข้องกับเจ้าของหนังสือโดยตรง

## อ่านตรงไหนก่อน

1. [Start Here](docs/00-start-here.md)
2. [Core Concepts](docs/01-core-concepts.md)
3. [Vision To Goals](docs/02-vision-to-goals.md)
4. [Goals, Tactics, Concepts, And Milestones](docs/03-goals-tactics-milestones.md)
5. [Model Work Week](docs/04-model-work-week.md)
6. [Weekly Execution](docs/05-weekly-execution.md)
7. [AI Facilitator Guide](docs/06-ai-facilitator-guide.md)
8. [Anti-Patterns](docs/08-anti-patterns.md) — โดยเฉพาะกับดัก Brain Dump First
9. [Traceability](docs/09-traceability.md) — บังคับ chain `Vision -> Goal -> Tactic -> Weekly`
10. [Productive Urgency](docs/10-productive-urgency.md) — ใช้ความเร่งให้เลือกแคบ ไม่ใช่ panic

## สรุปแก่นที่ห้ามพลาด

```text
Vision -> Intentional Imbalance -> 1-3 Goals -> Tactics -> Weekly Plan -> Scorecard -> Time Blocks
```

ถ้าข้ามชั้น ระบบจะเพี้ยน

## นิยามสั้น

**Intentional imbalance** = รอบนี้จะให้พลังกับเรื่องไหน และยอมให้เรื่องไหนเป็น maintenance/park

ไม่ใช่ quota ว่าต้องเลือก 3 ด้านชีวิต

**Goal** = outcome ที่วัดได้ภายใน 12 สัปดาห์

จำนวน goal ควรมี 1-3 ข้อ ไม่เกินนี้

**Concept** = แนวคิดกว้าง เช่น `ออกกำลังกาย`, `หา referral`, `จัดบ้าน`

**Milestone** = checkpoint หรือ deliverable เช่น `campaign พร้อม`, `ห้องจัดเสร็จ`

**Tactic** = action ที่ commit ทำจริง มี frequency หรือ due week และ score ได้

ตัวอย่าง:

```text
Ask for referrals 2x/day.
Send 5 personal notes/week.
Do cardio 2x/week for at least 20 minutes.
```

## ความผิดพลาดที่ repo นี้กันไว้

- AI เขียน goal เกิน 3
- AI เอา concept มาเป็น tactic
- AI เอา milestone มาเป็น tactic
- AI ใช้ Strategic Block ทั้งก้อนเป็นคาบเรียนของ goal เดียว
- AI เริ่มจาก brain dump / handoff แล้วค่อยแปะ vision link ย้อนหลัง
- Vision, 12W Plan, tactics, Weekly Plan ไม่ align กัน
- เอา urgency ไปยัดงานเพิ่ม แทนที่จะใช้ตัด scope
- weekly plan กลายเป็น to-do list มั่ว ไม่ได้ดึงจาก 12W Plan
- intentional imbalance กลายเป็น "เลือก 3 ด้านชีวิต" ทั้งที่จริงคือการเลือกน้ำหนัก

## ถ้าใช้ Obsidian

ดู [Obsidian Recommended Setup](docs/implementation/obsidian-recommended-setup.md)

ชื่อไฟล์แนะนำ:

```text
12WY/
  00-Start-Here.md
  Vision.md
  Cycle-Charter.md
  12W-Plan.md
  Model-Work-Week.md
  Commitment.md
  1-12W-Plan.md
  1-12W-Score.md
  past-weeks/
```

ใช้ `12W-Plan.md` เป็น default ไม่ใช้ `00-12wy-plan.md` เพราะ `00-` ควรเป็นหน้า index/start here
