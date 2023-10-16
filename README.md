# Numerical Methods for Computers
Offical Repository of RMUTT 09131201 Numerical Methods for Computers

Lecturers:
 - Wongwisarut Kuangsatung, Asst.Prof.Dr.
 - Ratthaprom Promkam, Dr.rer.nat

![Banner](./materials/banner.jpg)


## Schedules

SEMESTER 1/2566

| Section | Date    | Lecture  | Workshop | MS-Team Code | [D-Learn](https://dlearn.rmutt.ac.th/course/view.php?id=2317) Key |
|---------|---------|----------|----------|--------|---------|
|  SEC01  | TUE     |ST1910 เวลา 08.00 - 10.00 | ST1905 เวลา 10.00 - 12.00 | `d2q057d` |   |
|  SEC02  | TUE     |ST1910 เวลา 13.00 - 15.00 | ST1905 เวลา 15.00 - 17.00 | `6fzyujp` |   |
|  SEC03  | WED     |ST1910 เวลา 08.00 - 10.00 | ST1905 เวลา 10.00 - 12.00 | `vv07swc` |   |


## Examinations

| Section | MIDTERM | FINAL  | Location|
|---------|---------|-------|---------|
| SEC 01 | 28 สิงหาคม 2566 เวลา 09.00 - 12.00  | 30 ตุลาคม 2566 เวลา 13.00 - 16.00  | TBA |
| SEC 02 | 28 สิงหาคม 2566 เวลา 09.00 - 12.00  | 30 ตุลาคม 2566 เวลา 13.00 - 16.00 |  TBA |
| SEC 03 | 28 สิงหาคม 2566 เวลา 13.00 - 16.00 | 30 ตุลาคม 2566 เวลา 09.00 - 12.00 | TBA |


## Course Description

เครื่องมือสำหรับแก้ปัญหาเชิงตัวเลข การวิเคราะห์ความคลาดเคลื่อน ผลเฉลยของสมการแบบไม่เชิงเส้น ผลเฉลยของระบบสมการเชิงเส้น การประมาณค่าในช่วง การประมาณค่ากำลังสองน้อยที่สุด อนุพันธ์และปริพันธ์เชิงตัวเลข ผลเฉลยเชิงตัวเลขของสมการเชิงอนุพันธ์ การแก้ปัญหาเชิงตัวเลขด้วยคอมพิวเตอร์ และการประยุกต์ใช้เครื่องมือสำหรับแก้ปัญหาเชิงตัวเลข

Tools for numerical problem solving, error analysis, solutions of nonlinear equations, solution of systems of linear equations, interpolation, least square approximation, numerical diffentiation and integration, numerical solution of differential equations, numerical problem solving by computer, applying in tools for numerical problem solving

## Class Materials

|    Topic   |   Description   |    Materials and Workshops   |
|------------|-----------------|---------------|
| Erorrs and Approximation | ค่าคลาดเคลื่อนและค่าประมาณ | [Lecture](./materials/lecture_01.pdf) <br> [Workshop 01](./materials/workshop_01.ipynb) |
| Root Finding | รากของสมการ | [Lecture](./materials/lecture_02.pdf) <br> [Workshop 02](./materials/workshop_02.ipynb) <br>  [Workshop 03](./materials/workshop_03.ipynb)|
| Systems of Linear Equations | ระบบสมการเชิงเส้น | [Lecture](./materials/lecture_03.pdf) <br> [Workshop 04](./materials/workshop_04.ipynb) <br> [Workshop 05](./materials/workshop_05.ipynb) <br> [Workshop 06](./materials/workshop_06.ipynb) <br> [Workshop 07](./materials/workshop_07.ipynb)|
| Regression | สมการถดถอย | [Lecture](./materials/lecture_04.pdf) <br> [Workshop 08](./materials/workshop_08.zip) <br> [Workshop 09](./materials/workshop_09.zip) |
| Interpolation | การประมาณค่าในช่วง | [Lecture](./materials/lecture_05.pdf) <br> [Workshop 10](./materials/workshop_10.ipynb) <br> [Workshop 11](./materials/workshop_11.zip) |
| Numerical Differentiation | อนุพันธ์เชิงตัวเลข | [Lecture](./materials/lecture_06.pdf) <br> [Workshop 12](./materials/workshop_12.ipynb) |
| Numerical Integration | ปริพันธ์เชิงตัวเลข | [Lecture](./materials/lecture_07.pdf) <br> [Workshop 13](./materials/workshop_13.ipynb) |


## Grades

คะแนนเต็ม 100 คะแนน โดยแบ่งออกเป็น
- การสอบกลางภาค 25%
- การสอบปลายภาค 25%
- การสอบย่อย 25%
- งานที่ได้รับมอบหมาย 25%

หากนักศึกษาเข้าเรียนน้อยกว่า 80% ของเวลาเรียนทั้งหมด
หรือได้คะแนนรวมน้อยกว่า 50% ของคะแนนเต็ม นักศึกษาจะไม่ผ่านในรายวิชานี้ และได้รับการบันทึกผลการเรียน F (เกรด 0.0) 

สำหรับนักศึกษาที่ผ่านเกณฑ์ดังกล่าว จะได้รับการบันทึกผลการเรียนตามเกณฑ์ของคะแนน t-score 

```
t-score = 50 + 10*(x - u)/s
```
เมื่อ x คือคะแนนรวม, u คือคะแนนเฉลี่ยของคะแนนรวม และ s คือส่วนเบี่ยงเบนมาตรฐานของคะแนนรวม

ดังนี้

| ผลการเรียน | เกรด | เกณฑ์ t-score |
|---------|------|--------------|
| F | 0.00 | (-Inf, 50) | 
| D | 1.00 | [50, 55) | 
| D+ | 1.50 | [55, 60) | 
| C | 2.00 | [60, 65) |
| C+ | 2.50 | [65, 70) |
| B | 3.00 | [70, 75) |
| B+ | 3.50 | [75, 80) |
| A | 4.00 | [80, Inf) |

## References

- Steven C. Chapra and Raymond P. Canale, (2015) Numerical Methods for Engineers 7th edition, McGraw-Hill Education, 2Penn Plaza, New York.
- Burden, R. L., & Faires, J. D. (2005). Numerical Analysis (8th ed.). Belmont, CA: Thompson Brooks/Cole.
- ปราโมทย์ เดชะอำไพ และนิพนธ์ วรรณโสภาคย์, (2010) ระเบียบวิธีเชิงตัวเลขในงานวิศวกรรม, สำนักพิมพ์จุฬาลงกรณ์มหาวิทยาลัย
- วรสิทธิ์ กาญจนกิจเกษม, (2014) ระเบียบวิธีเชิงตัวเลข, สำนักพิมพ์จุฬาลงกรณ์มหาวิทยาลัย