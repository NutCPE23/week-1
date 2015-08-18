# Instruction

## Read and understand the code, the logic behind it, the limitation of it
* Answer the question 1 - 4 below (you can edit this file directly)
* Change the code such that it will sort from larger to smaller, put the revision of your code below
* Change the code such that there is no flag variable, put the commit number below and answer question 5 


## Revision, put your commit number here
* Sort from larger to smaller: 
* Without flag:

## Questions
1. How this code can sort number from smaller to larger
 
Answer: ใช้ลูป เปรีียบเทียบตัวเลข 2 ตัวที่อยู่ติดกัน แล้วสลับเลขหากเลขตัวหน้ามีค่ามากกว่าเลขตัวหลัง  ทำซ้ำไปเรื่อยๆจนครบทุกตำแหน่ง

2. What if two numbers equal, what will happen? 

Answer: ไม่เกิดการสลับที่กัน

3. How many times at line 24 will be executed (as a function of the size of input) 

Answer: n*n

4. Why we need flag variable ? 

Answer: เพื่อช่วยให้โปรแกรมทำงานได้รวดเร็วขึ้นเพราะไม่จำเป็นต้องเช็คจนหมดทุกตำแหน่ง

5. When we remove the flag variable, the code will run faster or slower? in which scenario? 

Answer: ช้าลง เพราะ หากไม่ใช้ตัวแปล flag แล้ว โปรแกรมจะต้องทำการวนลูปไปจนตรวจสอบครบทุกตำแหน่ง ในทุกๆครั้ง แม้ชุดตัวเลขจะเรียงกันเรียบร้อยแล้วก็ตาม