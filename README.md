[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/w8H8oomW)
**<ins>Note</ins>: Students must update this `README.md` file to be an installation manual or a README file for their own CS403 projects.**

**รหัสโครงงาน:** 67-1_13_pps-r1

**ชื่อโครงงาน (ไทย):** ระบบแนะนำอัตโนมัติสำหรับการหางานโดยใช้เทคนิคการประมวลผล
 ภาษาธรรมชาติ 

**Project Title (Eng):** Recommendation System for Job Finding using Natural Language 
Processing Techniques

**อาจารย์ที่ปรึกษาโครงงาน:** ผศ.ดร.ปกป้อง ส่องเมือง

**ผู้จัดทำโครงงาน:**
1. นายภัทรพล ทองยอดแก้ว  6409682579  pattarapol.ton@dome.tu.ac.th
   
Manual / Instructions for your projects starts here !
#  ติดตั้ง vscode และ Git
   1. ติดตั้ง Visual Studio Code
   2. ติดตั้ง Python 3.8+ ใน Visual Studio Code
   3. ติดตั้ง Jupyter Extension สำหรับ VS Code
   4. VS Code + Jupyter Extension for VS Code
   5. ติดตั้ง git ผ่านลิงค์ https://git-scm.com/downloads/win
#  วิธีการติดตั้งและตั้งค่าไฟล์โปรเจค (bash)
1. Clone โปรเจกต์จาก GitHub

git clone https://github.com/ComSciThammasatU/2567-2-cs403-final-submission-67-1_13_pps-r1.git

cd job-recommendation-system
      
2. ติดตั้ง dependencies (ดูทั้งหมดใน requirements.txt): pandas, numpy, scikit-learn, sentence-transformers, tqdm, etc.
      pip install -r requirements.txt
      
# วิธีการใช้งานโปรแกรม
1. 📁 โครงสร้างไฟล์ข้อมูล
โค้ดทั้งหมดจะอยู่ในไฟล์โน้ตบุ๊กนี้: Notebooks/ ซึ่งจะประกอบไปด้วย "final_RS_Doc2Vec.ipynb", "final_RS_SBERT.ipynb", "final_RS_TF-IDF.ipynb"
ภายในโน้ตบุ๊กจะมีการโหลดข้อมูลจากไฟล์: Data/ ซึ่งจะประกอบไปด้วย "course_data.xlsx" และ "job_data.xlsx"

*โปรดตรวจสอบว่าโฟลเดอร์ data/ อยู่ในตำแหน่งที่ถูกต้องสัมพัทธ์กับไฟล์โน้ตบุ๊ก เมื่อเปิดใช้งานผ่าน VS Code*

2. ▶️ วิธีการใช้งานโปรแกรม
2.1 เปิด VS Code
2.2 เปิดโฟลเดอร์โปรเจกต์ชื่อ 2567-2-cs403-final-submission-67-1_13_pps-r1
2.3 เปิดไฟล์โน้ตบุ๊ก: เช่น "final_RS_SBERT.ipynb"
   รันแต่ละเซลล์ในโน้ตบุ๊กตามลำดับ เพื่อดูผลลัพธ์:
   #1 โปรแกรมโหลดข้อมูลรายวิชาและตำแหน่งงานและ embed ข้อมูล
   #2 ระบบประมวลผลความเหมาะสมระหว่างโปรไฟล์นักศึกษากับคำอธิบายงาน
   #3 แนะนำรายวิชาที่ควรเรียนเพิ่มเติม เพื่อเพิ่มโอกาสในการสมัครงาน

**รูปภาพ Directory tree ของโปรแกรมงาน**

![image](https://github.com/user-attachments/assets/451d3047-07fa-4e3b-85df-bf521aa3143e)

