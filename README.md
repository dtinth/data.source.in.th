# data.source.in.th

**รวมชุดข้อมูลสาธารณะในไทย พร้อมให้คิวรีได้ทันทีบน Google BigQuery** โปรเจกต์นี้มีจุดมุ่งหมายเพื่อให้ทุกคนเข้าถึงข้อมูลสาธารณะในไทยได้ง่าย เหมาะสำหรับผู้ที่กำลังเรียนรู้เรื่อง Database, SQL หรือ Data Science

[BigQuery Sandbox](https://docs.cloud.google.com/bigquery/docs/sandbox) เปิดให้ทุกคนสามารถคิวรีข้อมูลได้ฟรี 1 TB ต่อเดือน เพียงแค่มีบัญชี Google โดยสามารถใช้งานผ่านเว็บเบราว์เซอร์ได้เลย ไม่ต้องติดตั้งโปรแกรมอะไรเพิ่มเติม

[**👉 เข้าดูโปรเจกต์ใน BigQuery Studio**](https://console.cloud.google.com/bigquery?project=sourceinth)

## WeVis

ชุดข้อมูลจากโครงการของ [WeVis](https://wevis.info/)

| ชุดข้อมูล | คำอธิบาย |
| --- | --- |
| [`wevis_thbudget69_20250525`](https://console.cloud.google.com/bigquery?project=sourceinth&ws=!1m4!1m3!3m2!1ssourceinth!2swevis_thbudget69_20250525) | ข้อมูลร่าง พ.ร.บ. งบประมาณรายจ่ายประจำปี 2569 จาก[เอกสารสำนักงบประมาณ](https://www.bb.go.th/topic3.php?gid=860&mid=544) ที่ผ่านกระบวนการ Digitize โดยโครงการ [สำรวจงบประมาณปี 69 (Thailand Budget 2569)](https://wevis.info/thbudget69/) โดยทีมงาน WeVis และอาสาสมัคร |

## ParliamentHack

ชุดข้อมูลจากโครงการ [Open Parliament Hackathon 2024 #ParliamentHack](https://hack.parliament.go.th/)

| ชุดข้อมูล | คำอธิบาย |
| --- | --- |
| [`lis_20240729`](https://console.cloud.google.com/bigquery?project=sourceinth&ws=!1m4!1m3!3m2!1ssourceinth!2slis_20240729) | ข้อมูลจาก [LIS](https://lis.parliament.go.th/) (ระบบสารสนเทศด้านนิติบัญญัติ) ติดตามสถานะกระบวนการนิติบัญญัติในห้องประชุมใหญ่ เช่น ร่างกฎหมาย, ญัตติ, กระทู้ถาม และผลการลงมติ |
| [`msbis_20240718`](https://console.cloud.google.com/bigquery?project=sourceinth&ws=!1m4!1m3!3m2!1ssourceinth!2smsbis_20240718) | ข้อมูลจาก [MSBIS](https://msbis.parliament.go.th/) (ระบบฐานข้อมูลรายงานและบันทึกการประชุมสำนักงานเลขาธิการสภาผู้แทนราษฏร) รวบรวมรายงานการประชุมย้อนหลังตั้งแต่ปี 2475 (เริ่มมี Full-text ช่วงปี 254x เป็นต้นมา) |

## thailand-geography-data

ชุดข้อมูลจากโครงการ [Thailand Geography Data](https://github.com/thailand-geography-data/thailand-geography-json)

| ชุดข้อมูล | คำอธิบาย |
| --- | --- |
| [`thailand_geography`](https://console.cloud.google.com/bigquery?project=sourceinth&ws=!1m4!1m3!3m2!1ssourceinth!2sthailand_geography) | รวบรวมข้อมูลรายชื่อจังหวัด อำเภอ ตำบล และรหัสไปรษณีย์ (มีทั้งภาษาไทยและภาษาอังกฤษ) จากโครงการ [Thailand Geography JSON](https://github.com/thailand-geography-data/thailand-geography-json) |

## การมีส่วนร่วม

หากมีข้อเสนอแนะเกี่ยวกับชุดข้อมูลอื่นๆ สามารถ [เปิด Issue บน GitHub](https://github.com/dtinth/data.source.in.th/issues) พร้อมระบุรายละเอียดและแหล่งที่มาของชุดข้อมูลนั้นๆ ได้เลย