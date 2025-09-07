🎯 Missions

#### Mission 1: Merge พัง

**อธิบาย**: Branch feature-A ถูก merge มาผิด ทำให้ไฟล์ src/app.js หายไปบางส่วน

**งาน**: กู้ branch feature-A กลับมาก่อน merge นั้น (ใช้ reset หรือ revert ได้)

**เป้าหมาย**: src/app.js ต้องกลับมาพร้อมโค้ดจาก feature A เเละ feature-A-01

#### Mission 2: Merge มั่ว โค้ดหาย

**อธิบาย**: Branch feature-B โดน merge มั่วจาก brach อื่นๆ ทำให้โค้ดบางส่วนไม่สมบูรณ์ เทสไม่ผ่านก่อนที่จะmerge เข้า main

**งาน**: feature-B ให้มีโค้ดที่สมบูรณ์ทั้งหมด โดยจะต้องสามารถ `console.log("Hello Workshop B")` ได้

**เป้าหมาย**:

1. เข้าใจว่า `console.log("Hello Workshop B")` ที่อยู่ใน `feature/B-01` หายไปได้ยังไง เวลาที่ merge `feature/B-01` เข้า `feature/B`
2. จุดไหนที่เพิ่ม `console.log("Hello Workshop B")` เข้าไป
3. เเนวทางการเเก้ไข
