### ผลที่ได้จากการรันคำสั่งในข้อ 3

![4](https://github.com/Nitiphum7/03376836-OOP-2566-Lab-12/assets/144196695/89ba0d47-64f9-4e84-95b9-4eadf76710e9)


โปรแกรม Build ได้เพราะมีการเรียกใช้เมท็อด CalculateArea() แต่ละคลาสเพื่อคำนวณพื้นที่ของรูปทรงต่าง ๆ

### ผลที่ได้จากการรันคำสั่งในข้อ 5


![Uploading 4.png…]()

โปรแกรม Run ได้เพราะ Shape ประกาศเมท็อด CalculateArea() เป็น abstract ทำให้แต่ละคลาสลูกต้องโอเวอร์ไรด์เมท็อด CalculateArea() ตามลักษณะของรูปทรงนั้น ๆ

### สิ่งที่พบในการทดลอง
- โปรแกรม Build ได้เพราะมีการเรียกใช้เมท็อด CalculateArea() แต่ละคลาสเพื่อคำนวณพื้นที่ของรูปทรงต่าง ๆ และ Shape ประกาศเมท็อด CalculateArea() เป็น abstract ทำให้แต่ละคลาสลูกต้องโอเวอร์ไรด์เมท็อด CalculateArea() ตามลักษณะของรูปทรงนั้น ๆ
- ผลลัพท์ที่ได้ คือ
  - Rectangle Area = 10.00000 x 20.00000 = 200.00000 unit(s)
  - Triangle Area = 10.00000 x 20.00000 x 1/2  = 100.00000 unit(s)
  - Circle Area = 3.14159 x 10 ^2  = 314.15927 unit(s)

