Project: Student Marks Input System with Grade Calculation
Overview:
This project is a Python-based program designed to allow users to input their marks for various subjects and calculate the total marks, percentage, and grade. The program provides personalized feedback based on the student's performance. Users can input multiple records, and the program will continue until the user decides to stop.

Features:
Dynamic Data Input: The program collects the student's name, roll number, and marks for each subject.
Marks Calculation: The total marks (out of 800) and percentage are computed automatically.
Grade Calculation: Based on the percentage, the student is assigned a grade (A+, A, B, C, or F).
Motivational Feedback: The program provides personalized feedback based on the student's grade to encourage continuous improvement.
Multiple Record Entries: The user has the option to input multiple student records until they choose to stop.
Grade Criteria:
A+: 80% - 99% (Excellent work!)
A: 70% - 79% (Great job!)
B: 60% - 69% (Good effort!)
C: 50% - 59% (You passed!)
F: Below 50% (Don't be discouraged!)
How the Program Works:
User Input: The program asks the user to input the name and roll number of the student, followed by the marks for eight subjects: Mathematics, Urdu, Science, Islamiat, Computer Science, PST (Pakistan Studies), Sindhi, and English.

Calculations:

It calculates the total marks by summing up the individual marks of the subjects.
The percentage is calculated by dividing the total marks by the maximum possible marks (800) and multiplying by 100.
Based on the percentage, the program assigns a grade and provides motivational feedback based on the grade.
Feedback: The feedback is personalized and motivates the student to keep working hard, whether they did exceptionally well or need improvement.

Record Insertion: The student’s record is added to a list, and the program displays all entered records at the end of each input. The user is asked if they want to enter more records, and the program continues until the user inputs 'N' to stop.

Example:
Enter you name:fatima
Enter your rollnumber:001
Write marks of subjects that you obtained in exam. 
Enter your math marks(out of 100):76
Enter your urdu marks(out of 100):46
Enter your science marks(out of 100):86
Enter your islamiat marks(out of 100):94
Enter your computer marks(out of 100):46
Enter your pst marks(out of 100):75
Enter your sindhi marks(out of 100):35
Enter your english marks(out of 100):36
Good effort! You've earned a C grade. With more practice, you can do even better.
['Name:fatima,Roll-number:001,Math:76,Urdu:46,Science:86,Islamiat:94,Computer:46,Pst:75,Sindhi:35,English:36,Total marks:494 out of 800,Percentage:61.75%,Grade:F']
Record of fatima is inserted successfully. 
Do you want to insert more detail.If yes then write 'Y' and if not then write 'N'. Y
Enter you name:haider
Enter your rollnumber:002
Write marks of subjects that you obtained in exam. 
Enter your math marks(out of 100):64
Enter your urdu marks(out of 100):76
Enter your science marks(out of 100):86
Enter your islamiat marks(out of 100):38
Enter your computer marks(out of 100):64
Enter your pst marks(out of 100):37
Enter your sindhi marks(out of 100):46
Enter your english marks(out of 100):36
You passed! You've earned a D grade. Keep working hard and don't give up!
['Name:fatima,Roll-number:001,Math:76,Urdu:46,Science:86,Islamiat:94,Computer:46,Pst:75,Sindhi:35,English:36,Total marks:494 out of 800,Percentage:61.75%,Grade:F', 'Name:haider,Roll-number:002,Math:64,Urdu:76,Science:86,Islamiat:38,Computer:64,Pst:37,Sindhi:46,English:36,Total marks:447 out of 800,Percentage:55.88%,Grade:B']
Record of haider is inserted successfully. 
Do you want to insert more detail.If yes then write 'Y' and if not then write 'N'. Y
Enter you name:sir bilal
Enter your rollnumber:100
Write marks of subjects that you obtained in exam. 
Enter your math marks(out of 100):87
Enter your urdu marks(out of 100):69
Enter your science marks(out of 100):98
Enter your islamiat marks(out of 100):79
Enter your computer marks(out of 100):78
Enter your pst marks(out of 100):87
Enter your sindhi marks(out of 100):68
Enter your english marks(out of 100):98
Excellent work! You've scored an A+ grade. Keep up the amazing work!
['Name:fatima,Roll-number:001,Math:76,Urdu:46,Science:86,Islamiat:94,Computer:46,Pst:75,Sindhi:35,English:36,Total marks:494 out of 800,Percentage:61.75%,Grade:F', 'Name:haider,Roll-number:002,Math:64,Urdu:76,Science:86,Islamiat:38,Computer:64,Pst:37,Sindhi:46,English:36,Total marks:447 out of 800,Percentage:55.88%,Grade:B', 'Name:sir bilal,Roll-number:100,Math:87,Urdu:69,Science:98,Islamiat:79,Computer:78,Pst:87,Sindhi:68,English:98,Total marks:664 out of 800,Percentage:83.00%,Grade:C']
Record of sir bilal is inserted successfully. 
Do you want to insert more detail.If yes then write 'Y' and if not then write 'N'. N

Google Colab URL:
https://colab.research.google.com/drive/17MHF_re5bRG9A_rnQFW9aBroos4ECJcT?usp=sharing
