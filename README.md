Alumni Management Portal
Alumni Tracking System is an online-based application that helps to tracking of college graduates. The project aims to improve current tracking procedure of college graduate and providing alumni data to college faculties. It aims to developing a web portal which will be useful for the college to monitor the alumni and for the alumni to update their current status about the job activities.

Create dashboard pages for students and faculty:

Display the last 10 job advertisements.
Display 10 most recently applied job advertisements.
Display charts.
Add more features as you see fit.
Functional Requirements
Faculty/Students can register to the system.
Faculty/Students can only edit their own profile information.
Students can add job advertisements.
Can upload pictures/files of the job.
Optional: Use cloud services like Amazon S3 or Google Cloud Storage.
Students can only edit their own job advertisements.
Students can apply to the jobs.
Student's CV will be also visible to owners of the job advertisements that the student has applied.
Students and Faculty can filter job advertisements:
by tags.
by state.
by city
by companyName.
Faculty can filter students:
by state.
by city.
by major.
by name.
by student id.
Auto-complete tags while typing.
Faculty can write comments on students.
Only faculty members can see the comments.
Students can add their professional job experiences.
Admin can Activate/Deactivate students and faculty.
Admin can reset passwords.
Students and faculty can reset their password.
Users should follow a password reset link.
Use ECharts to create live charts for dashboards:
Number of job advertisements per location.
Number of students per state.
Number of students per city. (User should select the state.)
Tags.
Tags with location.
Average time spent to find a job per gpa range.
Add at least 4 more charts as you see fit.
All delete operations should be a soft deletion.
Log all user activities on the system.
Optional: Log data before/after for update operations.
Limit login attempts. If a user try to login with an invalid password more than 5 times, the system will lock the user and make it unable to login for 15 minutes.
OTP
The system will send randomly generated code to the user's email address.

Notifications
AppliedToTheJob: To the owner of the job advertisement when a student has applied to the job.
NewJobPoster: To all students who are interested in job poster's tags get a notification about the job.
Extra Features
You can pass with a Honor Grade by completing all extra features.

To get extra points:

All features of the project must be completed.
Prepare a deployment-ready docker image including dummy data and all configurations needed. Your project should run with docker-compose up command.
Prepare API documentation with Swagger.
Make sure you use the proper fetch strategies and explain them with comments.