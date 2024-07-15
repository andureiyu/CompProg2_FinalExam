In this activity you will create a CLI program that handles the the information the people, classrooms, and scheduling.

Here are the specifications that I need

Create a Student & Teacher Profile that inherits from Person class. These are the information needed

In Person class you need these following id which is a string, firstname which is a string, lastname which is a string, gender which is a char M or F, birthdate which is LocalDate. You should provider an accessor and mutator for it. Also add a getAge method to return the age of the person based on its birthdate. Lastly, add getFullName to return the full name in this format <Depending on gender Mr if M and F if female> <First Name> <Last Name>

In Student class it needs to be inherit from Person class with the additional properties course which is a string, yearlevel which is an int, & semester which is an int. Add an accessor and mutator for it. Also add a getCourseProgramStatus method that returns the course, yearlevel, & semeter as one with the following format <course> <yearlevel> <summer>.

In Teacher class it needs to be inherit from Person as well but with additional properties such as specialization as string and status as string ("FULL TIME" or "PART TIME" or "INACTIVE"). Provide an accessor and mutator to it. Also add a method called getStatus which returns either "FULL TIME" or "PART TIME" or "INACTIVE" depending on the teacher status

Create a Classroom which has the following properties id as string & name as string.

Lastly, create a Schedule class which has the following properties id as string, classroom as Classroom, teacher as Teacher, students as array Student, start_time as LocalData, end_time as LocalDate. Provide and accessor and mutator to it. If I do getClassroom it will just return the classroom name, If I do getTeacher it would return the name of the teacher through getFullName, If I do getStudents it would return all of the students available in the schedule in list use getFullName for it also.
Also add these mutator setClassroom that will set the classroom object, add addStudents that will just add a student to the schedule, add setTeacher that will set the teacher for that schedule.


Here are the files needed
1 - Person.java
2- Teacher.java
3-Student.java
4-Schedule.java
5-Classroom.java
