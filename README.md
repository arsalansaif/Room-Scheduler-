# Room-Scheduler-


All the tables in the database should be empty except the Rooms Table and the Dates Table. The Rooms table should contain three rooms, such as 101 with 60 seats, 102 with 40 seats,  and 201 with 20 seats, which will be used in this script. The Dates table should contain two dates, which will be expressed as date1 and date2 in this script.This scenario assumes that is the case.

The faculty names will be a, b, c, d, etc. to simplify input and this script.
The dates will be real dates but will be represented in this script by the symbolic names date1 and date2.

 

Script:

-Add faculty a
Note: after adding a faculty, the faculty should appear in the drop down list on the Reserve panel.

-Add faculty b

-Add faculty c

-Add faculty d

-Add faculty e

-Reserve a,  date1, 20

a reserves room 201
-Reserve b, date1, 50

b reserves room 101
-Reserve c, date1, 50

c gets waitlisted
-Reserve d, date1, 40

d reserves room 102
-Reserve e, date1, 20

e gets waitlisted
-Reserve c, date2, 20

c reserves room 201
-Status date1

 a reserved 201
 b reserved 101
 d reserved 102
-Status date2

 c reserved 201
-Status Waitlist 

 c date1 50
 e date1 20
General conditions of testing:

the results of any action are displayed to the user immediately after the action is performed without the user needing to check Status.
All affected combo boxes are updated immediately after each action is performed.
