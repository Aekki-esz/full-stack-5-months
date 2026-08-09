Git คือ ระบบ Version Control เอาไว้ติดตามการเปลี่ยนแปลงของไฟล์และโค้ดในเครื่องเรา
ส่วน GitHub คือแพลตฟอร์มบนคลาวด์ที่เอา Repository ของ Git ไปเก็บ แชร์ และทำงานร่วมกับคนอื่นได้

ภาพจำง่าย ๆ คือ:

VS Code / ไฟล์ในเครื่อง
↓
Working Directory
↓ git add .
Staging Area
↓ git commit
Local Repository
↓ git push
GitHub
Git เองแบ่งสถานะหลักของไฟล์เป็นแนวคิดประมาณ modified → staged → committed ซึ่งตรงกับ flow ด้านบนเลย

repository (Repo) = โฟลเดอร์โปรเจกต์ที่ Git คอยเก็บประวัติการเปลี่ยนแปลง
working Directory = ไฟล์ที่เรากำลังแก้อยู่ใน VS Code
staging Area = จุดพักก่อน Commit เหมือนเลือกก่อนว่า “รอบนี้จะบันทึกไฟล์ไหนบ้าง”
commit = Snapshot หรือจุดบันทึกหนึ่งช่วงของงาน
push = ส่ง Commit ที่อยู่ในเครื่องขึ้น GitHub
git status = เช็กว่าตอนนี้ไฟล์ไหนแก้แล้ว / staged แล้ว / ยังไม่ได้บันทึก

ตัวอย่างจากงานของคุณ
git add .
git commit -m "Day 01: Practice HTML text fundamentals"
git push

อ่านเป็นภาษาคนได้ว่า
git add .
= เตรียมไฟล์ที่เปลี่ยนไว้สำหรับบันทึก

git commit
= บันทึกเวอร์ชันนี้ไว้ในเครื่อง

git push
= ส่งเวอร์ชันที่บันทึกขึ้น GitHub
