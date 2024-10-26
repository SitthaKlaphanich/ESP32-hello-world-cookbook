# ESP32-hello-world-cookbook
## 1.ESP-IDF Example

เลือก hello_world หลังจากนั้นกด Create project

![image](https://github.com/user-attachments/assets/2e2fb33a-cc8a-4f10-ba24-208580b4dc91)

## 2.แก้ไข File
เข้าไปที่ main/hello_world_main.c เพือ แก้ไข ให้แสดงผลข้อความต่างๆ นอกเหนือจาก
hello world และให้โชว์ ข้อมูลต่างๆ ของ ESP32

![image](https://github.com/user-attachments/assets/65ebf47d-07a9-4c0e-8039-e12c36fe8b61)

## 3.แก้ไข code 
แก้ไขโค้ดใน main/hello_world_main.c
```
 printf("Hi ESP32\n"); //แสดงผลข้อมูล

for (int i = 1; i <= 12; i++) {
        printf("9 x %d = %d\n", i, i * 9);
} // กำหนด for loop ให้ i = 1 ถ้า i น้อยกว่าหรือจนกว่าเท่า 12 ให้ i++ ค่าไปเรื่อยๆ แล้วใช้ printf แสดงผลข้อมูลที่่กำหนด
```
หลังจากนั้น build flash เพื่อดูผลการทำงาน
   
![image](https://github.com/user-attachments/assets/317bb304-ae88-4e98-8e11-97ace0b85e85)

## 4.Build โปรเจค 
แสดงผล Hi ESP32 พร้อมสูตรคูณ แม่ 9

![image](https://github.com/user-attachments/assets/3a30f335-8b2a-4ea6-9228-99c61765a74b)

## 5.สรุป
คำสั่ง printf สามารถนำมาใช้ได้หลายรูปแบบ ตั้งแต่ แสดงข้อมูล ธรรมดา จนสามารถ นำมา
ใช้ ร่วมกับการบอกรายละเอียดของ ESP32 เพื่อแสดงผลผ่าน Serial Monitor





