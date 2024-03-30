# Exercise 9.1
![Ex9 1](https://github.com/65030179179Pattarapon/03376836-OOP-2566-Lab-15/assets/144198506/a5015905-47c2-4686-85be-18bd89fc50e9)

# Exercise 9.2
![Ex9 2](https://github.com/65030179179Pattarapon/03376836-OOP-2566-Lab-15/assets/144198506/8c3a9ff3-f0f3-4237-84e3-228d680d8790)

##
#### ในการทดลองนี้เรามีการใช้ Action Delegate เพื่อเรียกใช้เมธอดโดยไม่ต้องใช้พารามิเตอร์ และเรียกใช้เมธอดที่มีพารามิเตอร์หลายตัว พร้อมกับการใช้ Lambda Expression ในการกำหนดการทำงานของ Action Delegate ดังนี้:

- ประกาศตัวแปร Action a และกำหนดให้มีค่าเป็นเมธอด Print ซึ่งไม่มีการรับพารามิเตอร์ จากนั้นเรียกใช้งาน Action a ซึ่งจะเรียกใช้เมธอด Print เพื่อแสดงข้อความ "Hello World" ในหน้าจอ
- ประกาศตัวแปร Action s และกำหนดให้มีค่าเป็นเมธอด PrintSum ซึ่งรับพารามิเตอร์ 3 ตัว จากนั้นเรียกใช้งาน Action s โดยส่งพารามิเตอร์ 4, 5, และ 6 เข้าไป ซึ่งจะแสดงผลลัพธ์ว่า "sum = 15" ในหน้าจอ
- ประกาศตัวแปร Action sum และกำหนดให้มีค่าเป็น Lambda Expression ที่รับพารามิเตอร์ 2 ตัวและทำการบวกกัน จากนั้นแสดงผลลัพธ์ที่ได้ในหน้าจอ
- ประกาศเมธอด Print ที่ไม่รับพารามิเตอร์และแสดงข้อความ "Hello World" ในหน้าจอ
- ประกาศเมธอด PrintSum ที่รับพารามิเตอร์ 3 ตัวและทำการบวกกัน และแสดงผลลัพธ์ที่ได้ในหน้าจอว่า "sum = " รวมกันกับผลลัพธ์การบวกของพารามิเตอร์ทั้ง 3 ตัว ในรูปแบบของข้อความสตริง โดยใช้ string interpolation ใน C#