# th-cv-sentences

Thai sentences from Common Voice
https://commonvoice.mozilla.org/sentence-collector/

You can get lastest rejected text or approved text from Common Voice api
- rejected: [https://commonvoice.mozilla.org/sentence-collector/sentences/text/rejected/th](https://commonvoice.mozilla.org/sentence-collector/sentences/text/rejected/th)
- approved: [https://commonvoice.mozilla.org/sentence-collector/sentences/text/approved/th](https://commonvoice.mozilla.org/sentence-collector/sentences/text/approved/th)

## Rejected sentences
ประโยคที่ถูกปฏิเสธ
- rejected.txt - ประโยคที่ถูกปฏิเสธมาจาก Sentence Collector
- get-typos.txt - ลบประโยคที่มีภาษาอังกฤษ อักษรละติ ตัวเลข ไม้มยก ออกจาก rejected.txt เพื่อกรองให้เหลือเฉพาะประโยคที่น่าจะถูกปฏิเสธเพราะมีสะกดผิด หรือผิดไวยากรณ์ หรืออ่านยาก

## Generated sentences
- get-fake-data.ipynb - สร้างข้อมูลชื่อคน (จาก Faker) และข้อความแสดงจำนวน (สุ่มและใช้ PyThaiNLP อ่านจำนวนเป็นข้อความ)

## Data preparation
เตรียมชุดข้อมูล
- stocks.txt - ข้อมูลชื่อบริษัทและกองทุนในตลาดหลักทรัพย์ เตรียมจาก get-stocks.ipynb
