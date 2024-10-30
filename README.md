แนวทางการทำงาน ESP32_ESP-IDF_WiFi-STA cook book

1. ระบุตัวอย่างที่ใช้ ว่าเอามาจากตัวอย่างไหน
   - เลือก new project แล้วตั้งชื่อโปรเจค ที่เก็บโฟลเดอร์ และเลือก port
     <img width="1470" alt="ภาพถ่ายหน้าจอ 2567-10-30 เวลา 20 43 02" src="https://github.com/user-attachments/assets/274d797d-5fc5-44e5-b3f9-49b291015bd2">
     <img width="1470" alt="ภาพถ่ายหน้าจอ 2567-10-30 เวลา 20 43 15" src="https://github.com/user-attachments/assets/1bb90254-20a5-4f41-afe5-16ad0437dfae">
   - เลือกโปรเจค Wi-Fi Station Example แล้วกด create project
     <img width="1470" alt="ภาพถ่ายหน้าจอ 2567-10-30 เวลา 20 48 46" src="https://github.com/user-attachments/assets/5f4d5fa4-5031-4e52-9c50-2ceb56f7a044">

2. ระบุว่า จะแก้ไขตรงไหนบ้าง เพื่ออะไร

   - แก้ไขการตั้งค่า SSID และ password ของ wifi โดยไปที่ SDK Configuration Editor เพื่อให้ connec wifi
     ![image](https://github.com/user-attachments/assets/b5ff8bfb-0eac-48cc-946b-5c0d1daa8601)

3. แสดงขั้นตอนการทำ project

   - เมื่อตั้งค่า wifi เสร็จกด save แล้วทำการ build,flash and monitor

     #ถ้าเชื่อต่อ wifi ไม่สำเร็จจะขึ้น failed to connect ตามภาพด้านล่าง ให้ทำการเช็คการตั้งค่าการเชื่อมต่อ Full clean และ build,flash and monitor ใหม่
     ![image](https://github.com/user-attachments/assets/424e3422-2fa4-42ff-af75-e86fab94eb3e)

4. แสดงผลการทำ project
   - ถ้าเชื่อมต่อ wifi สำเร็จจะแสดงผล wifi station: connect to ตามภาพด้านล่าง
     ![image](https://github.com/user-attachments/assets/c71da6d6-e771-424e-bc58-4acf0a700cf3)

5. สรุปผลการทำ project
   - โปรเจคนี้จะตรวจสอบถ้าการเชื่อมต่อสำเร็จ terminal จะแสดงข้อมูล IP Address ที่ได้รับ
  

