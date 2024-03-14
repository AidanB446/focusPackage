# PCSB Focus Student Portal Package

Python package to get data from the Pinellas County Schools student Focus web application 
(https://focus.pcsb.org/focus/index.php).

Package is meant to be an easy and efficient way to get student data for Pinellas County Students.

#Install
pip install pcsbFocus==0.0.1

#Example

```
from pcsbFocus.focus import focus

student = focus("username", "password")

grades = student.getGrades()

schedule = student.getSchedule()

studentInfo = student.studentInfo()

schoolInfo = student.schooInfo()

student.quit()

```



