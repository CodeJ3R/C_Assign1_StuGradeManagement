# C_Assign1_StuGradeManagement
Designing a basic CLI program that can input data like names and grades, preform basic arithmetic operations, make decisions, implement loops, use different data types

1.	Student info
2.	Char garbage[holding x amount of inputs that aren’t numbers]
3.	Char studentsname[100]-suggested by nadia
4.	Int Studentgrades1 (for the first grade of subject)
5.	Int Studentgrades2 (for the second grade of subject)
6.	Int Studentgrades3 (for the third grade of subject)
7.	Int Totalgrades (for adding up all the grades of the student)
8.	Float classAverage (for holding classAverage number)
9.	Float studentaverage (The individual student averages)
10.	char yestocontinue (for the user to add more students)
11.	int totalstudents (how many students were entered)
12.	bool didstudentpass ( to indicate pass or fail)
13.	int classtotal (to add up all the marks for the class)
14.	bool nograde (need it for error catching)
15.	
16.	*Greeting Message*                   
17.	DO {
18.	Print “enter students info”
19.	*Scan for user input,*
20.	
21.	Return message that studentname has been added
22.	The totalstudent variable goes up by 1 (totalStudents++)
23.	
24.	Remind the user how many students have been entered thus far 
25.	print(total students)
26.	
27.	*Start of the first grade loop*
28.	WHILE(there is nograde) {
29.	*message* tell the user to enter a grade between 0-100
30.	
31.	IF (user enters something besides a number) {
32.	Respond with an error message and put the scanned input into the       garbage array} Loop back to tell the user to enter a grade between 0-100
33.	Continue
34.	}
35.	IF(user tries to enter a number lower than 0 and higher than 100)
36.	Return with error to enter a number between 0 and 100
37.	Loop back to tell the user to enter a grade between 0-100
38.	
39.	ELSE 
40.	Print message that first grade has been entered
41.	
42.	nograde becomes false because a grade has been entered
43.	
44.	Repeat code logic for entering second subjects grade
45.	
46.	Repeat code logic for entering second subjects grade
47.	
48.	
49.	Print message that all grades have been entered
50.	
51.	Add up the grades for the student
52.	totalgrades = studentgrade1 + studentgrade2+ studentgrade3
53.	
54.	Classtotal= classtotal+totalgrade // add students total to the class pile
55.	
56.	Studentaverage = float *changing the integers into float numbers* studentgrade 1 + studentgrade2 +studentgrade 3
57.	
58.	
59.	Print message to user the results of the students name,total grades, average and if they pass
60.	
61.	IF studentaverage is >=50.0  didstudentpass = true
62.	ELSE
63.	didstudentpass = false
64.	
65.	Print message that student passed or failed
66.	
67.	Print message that it finished evaluating student
68.	Ask user if they want to enter another student or not
69.	Yes or No
70.	}WHILE yesTocontinue == y);
71.	
72.	User pressing n;
73.	
74.	Print farewell message
75.	
76.	Print how many students were added
77.	
78.	Print class average (float) class total/totalstudents
79.	
80.	Print end of program
81.	
