# USING-CONDITIONAL-AND-LOOP
name = input(&quot;Enter Student Name: &quot;)
roll = input(&quot;Enter Roll Number: &quot;)
course = input(&quot;Enter Course Name: &quot;)
print(&quot;\nEnter marks out of 100:\n&quot;)
s1 = int(input(&quot;Subject 1: &quot;))
s2 = int(input(&quot;Subject 2: &quot;))
total = s1 + s2
percentage = total / 2
if percentage &gt;= 90:
grade = &quot;A+&quot;
elif percentage &gt;= 80:
grade = &quot;A&quot;
elif percentage &gt;= 70:
grade = &quot;B+&quot;
elif percentage &gt;= 60:
grade = &quot;B&quot;
elif percentage &gt;= 50:
grade = &quot;C&quot;
else:
grade = &quot;Fail&quot;
print(&quot;\n============== STUDENT MARKSHEET ==============&quot;)
print(&quot;Name :&quot;, name)
print(&quot;Roll Number :&quot;, roll)
print(&quot;Course :&quot;, course)
print(&quot;-----------------------------------------------&quot;)
print(&quot;Subject 1 :&quot;, s1)
print(&quot;Subject 2 :&quot;, s2)
print(&quot;-----------------------------------------------&quot;)
print(&quot;Total Marks :&quot;, total)
print(&quot;Percentage :&quot;, percentage, &quot;%&quot;)
print(&quot;Grade :&quot;, grade)
print(&quot;===============================================&quot;)

Output:
Enter Student Name: Ravi
Enter Roll Number: 101
Enter Course Name: Python
Enter marks out of 100:
Subject 1: 85
Subject 2: 92
============== STUDENT MARKSHEET ==============
Name : Ravi
Roll Number : 101
Course : Python
-----------------------------------------------
Subject 1 : 85
Subject 2 : 92
-----------------------------------------------
Total Marks : 177
Percentage : 88.5 %
Grade : A
===============================================
