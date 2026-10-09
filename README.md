# IQAir Widget — Legacy / Deprecated

> **เลิกใช้เป็นแหล่งพัฒนาหลักตั้งแต่ 9 ตุลาคม 2026**
>
> **ระบบป้าย LED โรงพยาบาลอุทัยและลิงก์สำหรับหน่วยงานอื่น:** [aase7en/webapp-widget](https://github.com/aase7en/webapp-widget)

Repository นี้มี `index.html` สำหรับฝัง IQAir Widget ของผู้ให้บริการภายนอกโดยตรง ไม่ใช่ Backend ของรายงาน PM2.5 พื้นที่โรงพยาบาลอุทัย และไม่ใช่โครงการที่ใช้พัฒนาระบบใหม่ต่อไป

## เหตุใดจึงยังไม่ได้ลบ Repository

- GitHub Pages เดิมตอบ HTTP 200 อยู่ และยังไม่ยืนยันว่าไม่มีเว็บไซต์/จอ LED อื่นฝัง URL เดิม
- การลบ Repository อาจทำให้ Embedded Widgets ของผู้ใช้อื่นเสียทันที
- ให้ตรวจ URL dependencies และการใช้งานภายนอกก่อน แล้วค่อย Archive เป็นระยะเปลี่ยนผ่าน หรือ Delete หลังยืนยันแล้ว

## ใช้งานรุ่นใหม่

อ่านคู่มือ [webapp-widget README](https://github.com/aase7en/webapp-widget#readme) สำหรับ URL ที่กำหนด `lat`/`lon`, PM2.5, Heat Index และสถานะ Flood Monitoring ได้ โดยแยกข้อมูลแบบจำลองจากข้อมูลที่วัดได้จริง

**หมายเหตุ:** ขณะอัปเดต README นี้ ไม่มีการเปลี่ยน `index.html` หรือส่วนฝัง IQAir เดิม
