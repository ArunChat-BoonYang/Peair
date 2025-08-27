# Deploy-Scale-MeUp

โปรเจกต์นี้ใช้ AWS ในการ Deploy ระบบที่มีความสามารถในการขยายขนาดอัตโนมัติ โดยใช้ EC2, Lambda, หรือ Elastic Beanstalk


## สารบัญ
 - [Contributing](#contributing)
 - [วิธีการใช้งาน](#%E0%B8%A7%E0%B8%B4%E0%B8%98%E0%B8%B5%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B9%83%E0%B8%8A%E0%B9%89%E0%B8%87%E0%B8%B2%E0%B8%99)
 - [Prerequisites](#prerequisites)
 - [How to Run](#how-to-run)
 - [Monitoring](#monitoring)
 - [Security](#security)
 


## Contributing

 - นางสาวอรุณฉัตร  บุญยัง 6652300109
 - นางสาวดวงกมล   พูลเกษม 6652300222
 - นายเฉลิมพล     บรรณารรักษ์ 6652300371
 - นายคมกฤษณ์   ตังตติยภัทร์  6652300931

## Architect

## CI/CD Template
![enter image description here](https://github.com/ArunChat-BoonYang/Peair/blob/main/image/cicd%20template.png?raw=true)
![enter image description here](https://github.com/ArunChat-BoonYang/Peair/blob/main/image/cicd%20template%20%E0%B8%82%E0%B8%B2%E0%B8%A7.png?raw=true)
## Deployment

## Load test
## Auto-scaling
1.Scal Up
![enter image description here](https://github.com/ArunChat-BoonYang/Peair/blob/main/image/Scal%20up.png?raw=true)
2.Scal Down
![enter image description here](https://github.com/ArunChat-BoonYang/Peair/blob/main/image/scale%20down.png?raw=true)








## วิธีการใช้งาน

## Prerequisites
- AWS account
- IAM user กับสิทธิ์ที่เหมาะสม
- AWS CLI ติดตั้งในเครื่อง (ถ้าใช้ในการตั้งค่า)

## How to Run
1. **การเรียกใช้ API ผ่าน API Gateway**
   - สร้าง API Gateway ใน AWS Console
   - สร้าง API และเชื่อมต่อกับ Lambda หรือ EC2 instance
   - ใช้ endpoint URL ที่ได้จาก API Gateway เพื่อลองเรียก API

2. **การใช้งานผ่าน Elastic Beanstalk**
   - ใช้ AWS Elastic Beanstalk เพื่อดีพลอยแอปพลิเคชัน
   - อัปโหลดไฟล์ zip ที่ประกอบด้วยโปรเจกต์และคำสั่งการติดตั้ง (เช่น Dockerfile, web server config)
   - รอให้ Beanstalk ตั้งค่าและรันแอปพลิเคชันให้

## Monitoring
- ใช้ **AWS CloudWatch** เพื่อตรวจสอบ logs และ performance ของ EC2 หรือ Lambda
- ตรวจสอบสถานะและการขยายขนาดของระบบอัตโนมัติใน EC2 Auto Scaling

## Security
- ใช้ **IAM roles** ในการจัดการสิทธิ์การเข้าถึง
- ตั้งค่า **VPC** เพื่อแยก subnet และป้องกันการเข้าถึงที่ไม่ปลอดภัย

# M

