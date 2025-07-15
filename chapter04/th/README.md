# บทที่ 4: การทำงานร่วมกับ Remote Repository

## การเชื่อมต่อกับ Remote Repository (git remote add)
เชื่อมต่อ repository บนเครื่องกับ remote:
```
git remote add origin <repository-url>
```

## การส่งการเปลี่ยนแปลงขึ้นไป (git push)
ส่ง commit ขึ้น remote:
```
git push -u origin main
```

## การดึงการเปลี่ยนแปลงลงมา (git pull)
ดึง commit ล่าสุดจาก remote:
```
git pull origin main
```

## การโคลนโปรเจกต์ที่มีอยู่แล้ว (git clone)
คัดลอก repository จาก remote:
```
git clone <repository-url>
```

**ตัวอย่าง:**
หากต้องการเริ่มทำงานกับโปรเจกต์จาก GitHub ให้รัน `git clone https://github.com/yourname/my-project.git` เพื่อคัดลอกลงเครื่อง
