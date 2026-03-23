# BSC_DPDM2025 — HW1

**Chapter 1: Introduction to Data Mining**  
Patcharee Deeya · 663020583-0

---

## สารบัญ

| # | หัวข้อ |
|---|--------|
| 1 | [Why Data Mining?](#1-why-data-mining) |
| 2 | [What Is Data Mining?](#2-what-is-data-mining) |
| 3 | [A Multi-Dimensional View of Data Mining](#3-a-multi-dimensional-view-of-data-mining) |
| 4 | [What Kinds of Data Can Be Mined?](#4-what-kinds-of-data-can-be-mined) |
| 5 | [What Kinds of Patterns Can Be Mined?](#5-what-kinds-of-patterns-can-be-mined) |
| 6 | [What Kinds of Technologies Are Used?](#6-what-kinds-of-technologies-are-used) |
| 7 | [Applications](#7-applications) |
| 8 | [Major Issues in Data Mining](#8-major-issues-in-data-mining) |
| 9 | [A Brief History of Data Mining](#9-a-brief-history-of-data-mining) |
| 10 | [Summary](#10-summary) |

---

## 1. Why Data Mining?

โลกปัจจุบันผลิตข้อมูลมหาศาลจากธุรกรรมออนไลน์ โซเชียลมีเดีย และอุปกรณ์ดิจิทัลแบบ real-time ซึ่งมนุษย์ไม่สามารถวิเคราะห์ได้ทันด้วยตนเอง Data Mining จึงจำเป็นเพื่อ:

- เปลี่ยนข้อมูลดิบให้เป็น **insight** ที่ใช้งานได้จริง
- ค้นหา **hidden patterns** ที่ซ่อนอยู่ในข้อมูล
- **ทำนาย**เหตุการณ์ในอนาคต
- ทำให้การ**ตัดสินใจ**ขององค์กรแม่นยำขึ้น

---

## 2. What Is Data Mining?

Data Mining คือ **กระบวนการค้นหาความรู้จากข้อมูลขนาดใหญ่** โดยใช้เครื่องมือ เช่น Machine Learning, สถิติ และอัลกอริทึมเฉพาะทาง เพื่อสร้างแบบจำลองที่ช่วยตอบคำถามสำคัญ เช่น:

- ใครจะซื้อสินค้า?
- ลูกค้าคนไหนเสี่ยง churn?
- ยอดขายจะขึ้นเมื่อไหร่?

---

## 3. A Multi-Dimensional View of Data Mining

Data Mining มีหลายมุมมองพร้อมกัน:

| มุมมอง | ตัวอย่าง |
|--------|---------|
| **ตามงาน** | Classification, Clustering, Association |
| **ตามข้อมูล** | ตาราง, ข้อความ, ภาพ, วิดีโอ, เว็บ |
| **ตามเทคโนโลยี** | AI, Data Warehouse, Visualization |
| **ตามการประยุกต์** | การตลาด, การเงิน, สุขภาพ, อุตสาหกรรม |

---

## 4. What Kinds of Data Can Be Mined?

| ประเภท | ตัวอย่าง |
|--------|---------|
| **Structured** | ตารางในฐานข้อมูล |
| **Semi-structured** | XML, JSON |
| **Unstructured** | ข้อความ, รีวิว, โพสต์โซเชียล |
| **Multimedia** | ภาพ, เสียง, วิดีโอ |
| **Time-series / Streaming** | ราคาหุ้น, ข้อมูล IoT |
| **Spatial** | ข้อมูลแผนที่, GPS |
| **Web data** | Usage logs, clickstream |

---

## 5. What Kinds of Patterns Can Be Mined?

| Pattern | ความหมาย |
|---------|---------|
| **Classification** | ทำนายประเภท/กลุ่มของข้อมูล |
| **Clustering** | แบ่งกลุ่มโดยไม่มี label กำหนดไว้ล่วงหน้า |
| **Association Rules** | "ซื้อ A มักซื้อ B ด้วย" |
| **Sequential Patterns** | พฤติกรรมที่เกิดตามลำดับเวลา |
| **Outlier Detection** | ค้นหาข้อมูลที่ผิดปกติ |
| **Prediction** | ทำนายค่า เช่น ยอดขาย, ราคาหุ้น |

---

## 6. What Kinds of Technologies Are Used?

- **Database systems** — จัดเก็บและเรียกใช้ข้อมูล
- **Data Warehouse / OLAP** — วิเคราะห์ข้อมูลระดับองค์กร
- **Machine Learning & AI** — สร้างแบบจำลองอัตโนมัติ
- **Statistical Modeling** — พื้นฐานทางคณิตศาสตร์
- **Hadoop / Spark** — ประมวลผล Big Data แบบ distributed
- **Visualization Tools** — แสดงผลและสื่อสาร insight
- **Cloud Computing** — รองรับ scale ขนาดใหญ่

---

## 7. Applications

| อุตสาหกรรม | การประยุกต์ใช้ |
|-----------|--------------|
| **การตลาด** | Personalization, Customer segmentation |
| **ค้าปลีก** | Market basket analysis |
| **การเงิน** | Fraud detection, Credit scoring |
| **การแพทย์** | ทำนายโรค, วิเคราะห์ข้อมูลผู้ป่วย |
| **โทรคมนาคม** | คาดการณ์ Customer churn |
| **อุตสาหกรรม** | Predictive maintenance |
| **ออนไลน์** | ระบบแนะนำ เช่น TikTok, Netflix |

---

## 8. Major Issues in Data Mining

- **คุณภาพข้อมูล** — ข้อมูลที่มี noise หรือค่าขาดหาย (missing values)
- **ความเป็นส่วนตัว** — การใช้ข้อมูลส่วนบุคคลต้องระวังประเด็น privacy
- **Scalability** — รองรับ Big Data ได้อย่างมีประสิทธิภาพ
- **ความซับซ้อน** — ข้อมูลหลายรูปแบบและหลายแหล่งที่มา
- **การตีความ** — ผลลัพธ์ที่ได้อาจยากต่อการอธิบายให้ผู้ใช้เข้าใจ
- **การรวมข้อมูล** — บูรณาการข้อมูลจากหลาย source เข้าด้วยกัน

---

## 9. A Brief History of Data Mining

```
ยุคแรก   →  เริ่มจากสถิติพื้นฐานและการวิเคราะห์ข้อมูลแบบดั้งเดิม
  1980s   →  ฐานข้อมูลเชิงสัมพันธ์เติบโตอย่างรวดเร็ว
  1990s   →  บูรณาการ ML + DB → กำเนิด Data Mining / ก่อตั้ง SIGKDD
  2000s   →  ยุค Big Data ทำให้ Data Mining กลายเป็นเทคโนโลยีหลักขององค์กร
ปัจจุบัน →  เป็นส่วนหนึ่งของยุค AI เต็มรูปแบบ
```

---

## 10. Summary

> Data Mining คือกระบวนการเปลี่ยนข้อมูลจำนวนมากให้เป็นความรู้ที่ใช้งานได้จริง  
> โดยใช้เทคนิคหลากหลาย ทั้ง classification, clustering และ association rules  
> นำไปประยุกต์ใช้ได้ทุกอุตสาหกรรม และเป็นรากฐานสำคัญของเทคโนโลยีในยุค AI

| หัวข้อ | สรุป |
|--------|------|
| **Why Data Mining?** | โลกมีข้อมูลล้น ต้องดึง insight ออกมาใช้ |
| **What Is Data Mining?** | สกัดความรู้จากข้อมูลขนาดใหญ่ด้วย ML + สถิติ |
| **Multi-Dimensional View** | มองตามงาน, ข้อมูล, เทคโนโลยี, การประยุกต์ |
| **Data Types** | ตาราง, ข้อความ, ภาพ, วิดีโอ, สตรีม |
| **Patterns** | Classification, Clustering, Association, Outlier |
| **Technologies** | AI, DB, Warehouse, Big Data tools |
| **Applications** | การตลาด, การเงิน, การแพทย์, อุตสาหกรรม |
| **Major Issues** | คุณภาพข้อมูล, Privacy, Scalability |
| **History** | สถิติ → ฐานข้อมูล → ML → Big Data → AI |

---
**Course Work and Grading**
| รายละเอียด | คะแนน |
| :--- | :--- |
| Midterm (data prepocessing ปฏิบัติ (เดี่ยว))| 25% |
| Final(ทฤษฎี data mining (เดี่ยว)) | 25% |
| Project (data prepocessing + data mining (จัดกลุ่มเอง 5-6 คน)) | 20% |
| Homework (แบ่งกลุ่มใหม่ทุกครั้ง) | 15% |
| Quiz (เดี่ยว ถามในห้อง) | 10% |
| GitHub | 5% |

***Final Score = Score * %attendance***

----
**เอกสารการเรียน**
| บทที่ | Slides |
| :--- | :--- |
| 01 | [01Intro.pdf](01Intro.pdf) |
| 02 | [02Data.pdf](02Data.pdf) |
---

## สรุป
Data Mining คือกระบวนการดึงความรู้ที่มีประโยชน์จากข้อมูลจำนวนมาก  
ช่วยให้เข้าใจข้อมูลและใช้ในการตัดสินใจได้อย่างมีประสิทธิภาพ

*BSC_DPDM2025 · Chapter 1 · Patcharee Deeya 663020283-2*
