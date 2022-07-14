# **Bản Phân Tích Dữ Liệu Assignment**
## Bảng Syllabus
![image](https://user-images.githubusercontent.com/105901866/177117123-b9e01ed6-e22c-4a27-a67d-71ee882fafe9.png)
- Category

  > Tên danh sách các điểm thành phần của môn học :
  > - Labs (0-5)
  > - Progress Tests
  > - Assignment
  > - Practice Exam
  > - Final Exam

- Type

  > Các hình thức test định kỳ :
  > - Quiz
  > - On-going
  > - practice Exam
  > - final Exam

- Part

  > Số lượng bài test tương ứng với mỗi hình thức test

- Weight 

  > Tổng phần trăm điểm của mỗi dạng điểm thành phần

- Completion Criteria

  > Điều kiện điểm bắt buộc của mỗi điểm thành phần

- Duration

  > Thời gian và địa điểm thực hiện bài test

- CLO

- Question Type

  > Cấu trúc và dạng bài test

- No Question
  > Số câu hỏi trong bài test

- Knowledge and Skill
  > Kiến thức và kỹ năng được đề ra

- Grading Guide
  > 

- Note

***
## Bảng Academic Transcript
![image](https://user-images.githubusercontent.com/105901866/177205332-4ad24763-b7ec-43bb-99ed-6610d2f840ed.png)
- NO
  > Số môn học

- Subject code
  > Mã môn học

- Subject name
  > Tên đầy đủ các môn học

- Semester
  > Thời gian và năm học (SeasonYear)

- Group
  > Tên lớp học xác định theo khóa + kì học

- StartDate
  > Thời gian bắt đầu học môn học tương ứng

- EndDate
  > Thời gian kết thúc học môn học tương ứng

- Average Mark
  > Điểm trung bình của môn học

- Status
  > Trạng thái Passed(with conditions) or Not Passed 

***
## Bảng Student Transcripts
![image](https://user-images.githubusercontent.com/105901866/177566410-515c1ac4-78da-427e-a9f6-eef99ca087af.png)
- Grade category
  > Tên danh sách các điểm thành phần của môn học tương ứng giống Category ở bảng Syllabus

- Grade Item
  > Tên thành phần đầu điểm nhỏ

- Weight
  > Phần trăm đầu điểm chiếm tổng số trong tổng điểm môn học

- Value
  > Điểm đã đạt được khi test với các đầu điểm tương ứng


***
# ERD Diagram

![image](https://user-images.githubusercontent.com/105901866/179046836-749d8ab8-7821-4535-a9d1-4c405346034f.png)

***
# Xác Định Entities and Attribute 

## Student 
  >- StudentID
  >- FName
  >- LName
  >- Address
  >- Gender
  >- DOB
  >- Email

## Group
  >- GroupID
  >- GroupName
  >- Major

## Subject
  >- SubjectID
  >- SubjectName

## Semester
  >- SesID
  >- SesName
  >- StartDate
  >- EndDate

## Weight
  >- WeightID
  >- weight_details

## Instruct
  >- InstructID
  >- Know_Skill
  >- Grading_Guide
  >- Note
  >- CategoryID

## Category
  >- CategoryID
  >- CategoryName
  >- [Completion Criteria]
  >- Type

## Assessment
  >- AssID
  >- Part
  >- Duration
  >- [No Question]
  >- CLO
  >- Weight
  >- CategoryID
































