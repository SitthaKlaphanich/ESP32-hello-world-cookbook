# ESP32-hello-world-cookbook
1.ESP-IDF Example

เลือก hello_world หลังจากนั้นกด Create project

![image](https://github.com/user-attachments/assets/2e2fb33a-cc8a-4f10-ba24-208580b4dc91)

2.เข้าไปที่ main/hello_world_main.c เพือ แก้ไข ให้แสดงผลข้อความต่างๆ นอกเหนือจาก
hello world และให้โชว์ ข้อมูลต่างๆ ของ ESP32

![image](https://github.com/user-attachments/assets/65ebf47d-07a9-4c0e-8039-e12c36fe8b61)

3.แก้ไขโค้ดใน main/hello_world_main.c
```
 printf("Hi ESP32\n"); //แสดงผลข้อมูล

for (int i = 1; i <= 12; i++) {
        printf("9 x %d = %d\n", i, i * 9);
} // กำหนด for loop สูตรคูณแม่ 9  แล้วใช้ printf แสดงผลข้อมูลที่่กำหนด
```
หลังจากนั้น build flash เพื่อดูผลการทำงาน
   
![image](https://github.com/user-attachments/assets/317bb304-ae88-4e98-8e11-97ace0b85e85)






