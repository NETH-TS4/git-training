🎯 Missions

Mission 1: Merge พัง
• Branch feature-A ถูก merge มาผิด ทำให้ไฟล์ src/app.js หายไปบางส่วน
• งาน: กู้ branch feature-A กลับมาก่อน merge นั้น (ใช้ reset หรือ revert ได้)
• เป้าหมาย: src/app.js ต้องกลับมาพร้อมโค้ดจาก feature A เเละ feature-A-01

Mission 2: Merge มั่ว
• Branch feature-B โดน merge มั่วจาก brach อื่นๆ ทำให้โค้ดบางส่วนไม่สมบูรณ์ เทสไม่ผ่านก่อนที่จะmerge เข้า main
• งานของคุณ: feature-B ให้มีโค้ดที่สมบูรณ์ทั้งหมด โดยจะต้องสามารถ `console.log("Hello Workshop B")` ได้
• เป้าหมาย: รัน node src/app.js แล้วต้อง print ออกมาเป็น "Hello Workshop B" ขึ้นมาเป็นส่วนหนึ่งของระบบ
