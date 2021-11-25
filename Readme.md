# Week 15 #
### Learning git ignore ###

# Job description

1. สร้าง repository ของตนเอง โดยสมติให้มีไฟล์ index.php และ password.php และทำการยับยั้ง (ignore) ไม่ให้มีการส่งไฟล์ password.php ขึ้นไปบน remote repository
(ใน commit แรกให้ push ไฟล์ password.php ขึ้นมาด้วย)
 
2. สร้าง repository ของตนเอง แล้วสร้าง project ในภาษา C# ด้วย visual studio  (ยังไม่ต้อง build project)

|Commit| งานที่ต้องทำ|
|------| ----------|
|1 | push ไฟล์ทุกอย่างไว้บน remote repository|
|2 | ignore folder ชื่อ .vs|
|3 | build project แล้วทำการ ignore ไฟล์ที่เกิดจากการสร้างโดย Visual studio|
|4 | ให้ push ไฟล์  <b>*.exe</b>  ขึ้นบน  remote repository เพื่อให้ผู้คนที่ไม่มี Visual Studio ติดตั้งอยู่สามารถโหลดไปใช้งานได้|

3. สร้าง repository ของตนเอง ที่มี  gitignore ในภาษา python แล้วนำงานทั้งหมดที่ลงแล็บในครึ่งเทอมแรกมาใส่ไว้ใน repo นั้น

4. ส่งงานโดยการเขียน  link ไปยัง repo ไว้ในไฟล์ <Student ID>.md (เช่น 63030004.md) แล้ว Pull Request มาใน repo นี้
  
---
  
***หมายเหตุ***
  การลบไฟล์ที่ไม่ต้องการออกจาก local repo

```
  git rm -r --cached .
  git add .
  git commit -m"remove files in  git ignore list"
  git push 
```

--- 
 ***ข้อควรระวัง***
ก่อนทำการ Pull Request ให้ตรวจสอบก่อนเสมอว่า  Local และ remome  repository ของตนเองได้ทำการ sync กับ update ล่าสุดของ upstream 
มิฉะนั้นอาจจะไปลบ folder ของ Pull request ที่เพื่อนเพิ่งจะเพิ่มเข้าไป

![image](https://user-images.githubusercontent.com/567256/143408103-4e0c04de-bde4-4166-9758-5af5608c191c.png)


![image](https://user-images.githubusercontent.com/567256/143408495-94ce4da8-d93c-4433-88ed-2a0e6199c5e8.png)


|No|Action|
|---|-------|
|1| คลิก Fetch Upstream|
|2| คลิก Fetch Fetch and merge|

