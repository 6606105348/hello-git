# Git ครั้งแรก (สไลด์ 12)

ก่อนเริ่ม login GitHub ค้างไว้ก่อน

## ทำตามนี้ทีละขั้น

สเต็ป 1 สร้าง repo ของตัวเอง กด Use this template แล้ว Create a new repository ตั้งชื่อ hello-git กด Create

สเต็ป 2 กดปุ่ม . (จุด) บนหน้า repo จะเด้งเข้า github.dev ซึ่งก็คือ VS Code บนเว็บ ไม่ต้องลงอะไร

สเต็ป 3 เปิด README.md เติมชื่อเล่นตัวเองต่อจากบรรทัด ผู้เข้าอบรม แล้วไปแท็บ Source Control พิมพ์ commit ว่า add my name

สเต็ป 4 กด Commit and Push ด้านบน (ถ้าปุ่มเป็นลูกศร กดเลือก Commit and Push) กลับไปหน้า repo กด Commits จะเห็นชื่อตัวเองใน history

## ติดตรงไหน

หาแท็บ Source Control ไม่เจอ ดูไอคอนกิ่งไม้แยกสายทางซ้าย

ปุ่ม Commit กดไม่ติด ต้องพิมพ์ข้อความ commit ก่อน

ยังไม่เห็นชื่อ รอสัก 5 วิ แล้ว refresh หน้า GitHub

## เคยใช้ Git แล้ว? ลองสายส่งงานแบบทีมจริง

ทีมจริงเขาไม่ commit ใส่ main ตรงๆ เขาแยก branch แล้วเปิด Pull Request ให้พี่เลี้ยงดูก่อนค่อย merge ลองทำแบบนี้แทน

สเต็ป 1 สร้าง repo จาก template เหมือนด้านบน ตั้งชื่อ hello-git

สเต็ป 2 กดปุ่ม . เปิด github.dev

สเต็ป 3 คลิกชื่อ branch main ที่มุมล่างซ้าย พิมพ์ชื่อ branch ใหม่ เช่น add-ชื่อเล่น เลือก Create new branch

สเต็ป 4 เปิด README.md เติมชื่อเล่นตัวเอง

สเต็ป 5 ไปแท็บ Source Control พิมพ์ commit ว่า add my name กด Commit and Push ตอนนี้ของขึ้น branch ใหม่ ยังไม่แตะ main

สเต็ป 6 กลับไปหน้า repo บน GitHub จะมีแถบเหลือง Compare and pull request เด้งมา กดเลย ใส่หัวข้อสั้นๆ กด Create pull request

สเต็ป 7 ในหน้า PR กด Merge pull request แล้ว Confirm merge ชื่อก็เข้า main ดูใน Commits ได้

งานจริงคนกด merge คือพี่เลี้ยงหลังรีวิวเสร็จ วันนี้กดเองไปก่อนจะได้เห็นครบวง

อยากสนุกขึ้น จับคู่กัน คนนึงเปิด PR อีกคนเข้าไปกด Review แล้ว Approve ก่อนค่อย merge ได้ลองทั้งฝั่งส่งงานและฝั่งรีวิว
