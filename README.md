# DjangoSSE
Server-Sent Events เป็นเทคโนโลยีที่เซิร์ฟเวอร์สามารถส่งการอัปเดตข้อมูลไปยังไคลเอ็นต์โดยอัตโนมัติผ่านการเชื่อมต่อ HTTP ที่คงอยู่ตลอดเวลา เหมาะสำหรับการแจ้งเตือนแบบเรียลไทม์ การอัปเดตข่าวสาร หรือการแสดงผลข้อมูลที่เปลี่ยนแปลงบ่อย SSE ใช้ JavaScript API ที่ชื่อ EventSource ในการรับข้อมูล และรองรับเบราว์เซอร์หลัก ๆ ได้แก่ Firefox, Chrome, Opera, Safari และ Edge 

How to how to implement in django
ในการใช้ SSE ใน Django คุณต้องมีเว็บเซิร์ฟเวอร์แบบ asynchronous ซึ่ง Django เวอร์ชันใหม่รองรับการทำงานนี้ได้อย่างสมบูรณ์ด้วยความช่วยเหลือของเซิร์ฟเวอร์ ASGI เช่น Daphne

git clone https://github.com/sippanun65ubu/DjangoSSE.git
cd DjangoSSE
cd myproject
python manage.py runserver
