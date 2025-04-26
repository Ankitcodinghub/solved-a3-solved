# solved-a3-solved
**TO GET THIS SOLUTION VISIT:** [SOLVED: A3 solved](https://www.ankitcodinghub.com/product/solved-a3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;3038&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;6&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (6 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;SOLVED: A3 solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (6 votes)    </div>
    </div>
Create a GradeBook class that calculates a grade-point average for a set of grades and displays information. You can input A, a, B, b, C, c, D, d, F and f for grades. But the inputted data could also be any characters, upper case, lower case or special character. The system should detect an improper grade input and allow reentering information. The grade of A is worth 4 points, B is worth 3 points, etc. You can use GradeBook program of Fig. 5.9–Fig. 5.11(attached) as a starting point.

The GradeBook class has the following methods and attributes.

The GradeBook class has 3 private data members, courseName, letterGrades and countGrades.

a. The courseName has a string data type. It stores course name information.

b. The letterGrades is a 100 elements character array. It stores all the inputs information which include the letter grades and non-letter grade information. For example, if you put a, $, a, C, 1, ! for the first 6 inputs the letterGrades first six elements should store A, $, A, C, 1, !.

c. The countGrades is a 6 elements integer array. It stores the number of each letter grade and number of the error(s) input. For example, if you input 5 As, 6 Bs, 1 C, 2 Ds, 2 Es and 3 Fs, the countGrades array elements from 0 to 5 should contain 5, 6, 1, 2, 3 and 2.

It also has several public member functions, GradeBook, setCourseName, getCourseName, initializeData, displayMessage, inputGrades, displayGradeReport, displayInputs, calculateGrade and ~GradeBook.

a. The GradeBook function is a constructor. It takes a string and will initialize its data members’ data. The constructor also displays information which includes “The Grade Book Constructor is called”, “*****The end of Grade Book Constructor.*****” and the information in between these two statements.

b. The setCourseName function takes a string and does not return anything. This function sets information for the string private data, courseName. It takes only the first 30 characters of the input string. If the inputted string shorter than 30 it will take everything. If it is longer than 30 it will keep the first 30 characters and truncate the rest of the information.

c. The getCourseName function returns the private data, courseName, information. It does not accept any data.

d. The initializeData function does not take and return anything. It initializes the private data members.

e. The displayMessage function does not take and return anything. It displays “Welcome to the grade book for ” information.

f. The inputGrades function does not take and return anything. It generates loops to get any number(but it need to be less than 100) of proper data input. If the inputted data is not any one of the following A, a, B, b, C, c, E, d, F, and f, the program will show “****Incorrect letter grade entered.****” message. The loop will be ended by inputting Ctl + D, or Ctl + Z ( it depends on your computer system).

g. The displayGradeReport function does not accept and return any data. It displays “The total number of students receive grades is “, “Number of students who received each letter grade” and “The class average is’ information. The class average is displayed in one digit double value.

h. The displayInputs function does not accept and return any data. It displays “The data entered is listed at the following: ” as a heading and all the grades (information) entered in a 4 in a row tabulate format.

i. The calculateGrade function does not accept any data but return a double value. This function calculates the GPA (Grade Point Average) and return the data.

j. i.The ~GradeBook function is the destructor of the class. When it called it will clean up the memory and displays “Destructor is called” message.

This assignment comes with a CISP400V9A3.zip file. It includes four files (CISP400V9A3.cpp, CISP400V9A3.exe, GradeBook.cpp and GradeBook.h). The CISP400V9A3.exe file is an executable file. You can double click the file to get to the expecting result (see the picture below) of this assignment. The GradeBook.cpp and GradeBook.h are files coming from the textbook examples (Fig 5.9 and 5.10) which you can use so you don’t need to start from scratch. After you finish your implementation for the GradeBook class, you can put the CISP400V9A3.cpp, GradeBook h GradeBook.cpp in a project and then you should run to the same result as the CISP400V9A3.exe. Please be awarded that you can adjust only your program (GradeBook h and GradeBook.cpp) to generate the required result but not the code in CISP400V9A3.cpp file.

The following are the displays of the expecting results.

The beginning screen of the program.

At the beginning screen, type “aAbBcCdDfF” and hit “enter” key.

Type “A” and hit “enter” key, type “b” and hit “enter” key, type “C” and hit enter key, type “c” and hit enter key, type “D” and hit “enter” key, type “f” and hit “enter” key, and type “1” and hit “enter” key.

Type “123” and hit “enter” key

Type “! @ # ^” and hit “enter” key

Hold “ctrl(control) key and “z” key, release the keys and hit “enter” key

Please document the files (CISP400V9A3.cpp, GradeBook.h, and GradeBook.cpp) properly and zip them into a proper named zip file for this assignment (refer to the assignment section of the class syllabus) and submit it to the A3 dropbox of the D2L Website.

Worth 150 points

AD3

Create a GradeBook class that takes grades and student names and displays information in an arrange way. The program also calculates a grade-point average for the inputted grades. You can input A, a, B, b, C, c, D, d, F and f for grades. But the inputted data could also be any characters, upper case, lower case or special character. The system should detect an improper grade input and allow reentering information. The grade of A is worth 4 points, B is worth 3 points, etc. You can use GradeBook program of Fig. 5.9–Fig. 5.11(attached) as a starting point.

The GradeBook class has the following methods and attributes.

The GradeBook class has 4 private data members, courseName, letterGrades, countGrades, and studentName.

a. The courseName has a string data type. It stores course name information.

b. The letterGrades is a 100 elements character array. It stores all the inputs information which include the letter grades and non-letter grade information. For example, if you put a, $, a, C, 1, ! for the first 6 inputs the letterGrades first six elements should store A, $, A, C, 1, !.

c. The countGrades is a 6 elements integer array. It stores the number of each letter grade and number of the error(s) input. For example, if you input 5 As, 6 Bs, 1 C, 2 Ds, 2 Es and 3 Fs, the countGrades array elements from 0 to 5 should contain 5, 6, 1, 2, 3 and 2.

d. The studentName is a 100 element pointer character array. It stores students’ names.

It also has several public member functions, GradeBook, setCourseName, getCourseName, initializeData, displayMessage, inputData, inputGrades, displayGradeReport, displayGrade, displayAllStudentsandGrades, calculateGrade, inputStudentName, displayStudentname, and ~GradeBook.

a. The GradeBook function is a constructor. It takes a string and will initialize its data members’ data. The constructor also displays information which includes “The Grade Book Constructor is called”, “*****The end of Grade Book Constructor.*****” and the information in between these two statements.

b. The setCourseName function takes a string and does not return anything. This function sets information for the string private data, courseName. It takes only the first 30 characters of the input string. If the inputted string shorter than 30 it will take everything. If it is longer than 30 it will keep the first 30 characters and truncate the rest of the information.

c. The getCourseName function returns the private data, courseName, information. It does not accept any data.

d. The initializeData function does not take and return anything. It initializes the private data members.

e. The displayMessage function does not take and return anything. It displays “Welcome to the grade book for ” information.

f. The inputGrades function takes one integer and one character data and return an integer data. It generates loops to get any number (but it need to be less than 100) of inputs of proper grades and names. If the inputted grade is not any one of the following A, a, B, b, C, c, E, d, F, and f, the program will show “****Incorrect letter grade entered.****” message. The loop will be ended by inputting Ctl + D, or Ctl + Z (it depends on your computer system). I use the input integer to control which array element to store the character, and use the return integer to indicate a proper grade is set.

g. The displayGradeReport function does not accept and return any data. It displays “The total number sets of data input is “, “The total number of error input is “, “The total number of students receive grades is “, “Number of students who received each letter grade” and “The class average is’ information. The class average is displayed in one digit double value.

h. The calculateGrade function does not accept any data but return a double value. This function calculates the GPA (Grade Point Average) and returns the data.

i. The ~GradeBook function is the destructor of the class. When it called it will clean up the memory and displays “Destructor is called” message.

j. The inputData function does not take and return anything. It mainly to generate the “Enter the letter grades….” screen and call the inputGrades and inputStudentName functions.

k. The displayAllStudentsandGrades function does not take and return anything. It displays “The data entered is listed at the following: ” as a heading, the students’ names and all the grades (information) entered in a 4 in a row tabulate format.

l. The inputStudentName function takes an integer data and does not return any information. The function displays “Enter a student name”, get the inputted name, store the name and link the name to the studentName array. The integer argument is for indexing the array.

m. The displayStudentname function takes an integer data and does not return anything. It displays the indexed student’s name. The integer argument is for indexing.

n. The displayGrade function takes an integer data and does not return anything. It displays the indexed grade. The integer argument is for indexing.

The first screen of the program before entering any data should look like the right side of picture..

After the first screen and the user Exit the program, it should generate the right side picture. Please bbe awared that there is a display of “There is no data entered.

If we input 1, a, a student, b, b studentb, c, c studentcc, d, d studentddd, e, f, f studentffff as data input as the right side of picture and exit the program, we should get a display result as closed to the end of the picture. Be aware of the data display is center alignment.

If we input 1, 2, 3, 4, and 5 as data input as the right side of picture and exit the program, we should get a display result as at the closed end of the picture. Be aware of the data display is center alignment and no student name exist.

If we input a, a1 good student, a, a2 good student2, a, a3 good student33, b, b good student, b, b2 good student2, b, b3 good student33 as data input as the right side of picture and exit the program, we should get a display result as closed to the end of the picture. Be aware of the data display is center alignment.

This assignment comes with a CISP400V9AD3.zip file. It includes four files (CISP400V9AD3.cpp, CISP400V9AD3.exe, GradeBook.cpp and GradeBook.h). The CISP400V9AD3.exe file is an executable file. You can double click the file to get to the expecting result (see the picture below) of this assignment. The GradeBook.cpp and GradeBook.h are files coming from the textbook examples (Fig 5.9 and 5.10) which you can use so you don’t need to start from scratch. After you finish your implementation for the GradeBook class, you can put the CISP400V9AD3.cpp, GradeBook.h , and GradeBook.cpp in a project and then you should run to the same result as the CISP400V9AD3.exe. You can adjust only your program but not the program in CISP400V9AD3.cpp file.

Please document the files properly and zip CISP400V9AD3.cpp, GradeBook h , and GradeBook.cpp files into a proper named zip file for an assignment (refer to the assignment section of the class syllabus) and submit it to the A3 dropbox of the D2L Website.

Worth 180 points
