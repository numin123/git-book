# บทที่ 3: การทำงานกับสาขา (Branching)

## การสร้างและสลับสาขา (git branch, git checkout/git switch)
สร้าง branch ใหม่:
```
git branch <ชื่อสาขา>
```
สลับ branch:
```
git checkout <ชื่อสาขา>
```
หรือ
```
git switch <ชื่อสาขา>
```

**ตัวอย่าง:**
คุณต้องการทดลองฟีเจอร์ใหม่โดยไม่กระทบกับโค้ดหลัก ให้รัน `git branch feature-x` เพื่อสร้างสาขาใหม่ แล้ว `git switch feature-x` เพื่อเริ่มทำงานบนสาขานั้น

## การรวมสาขา (git merge)
รวม branch เข้ากับ branch ปัจจุบัน:
```
git merge <ชื่อสาขา>
```

**ตัวอย่าง:**
เมื่อทำฟีเจอร์เสร็จแล้ว ให้สลับกลับไปที่ `main` แล้วรัน `git merge feature-x` เพื่อรวมงานเข้าด้วยกัน
