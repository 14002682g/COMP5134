Leave Application system for a Human Resource department, in Java, with GUI

========================================
Source code:

- import the "COMP5134_14002682g" folder as existing project with Eclipse
- 5 packages:data, frame, leaveApplication, loginHandler and utils

========================================

Initail User login information

id: director
password: director

id: staff1
password: staff1

id: staff2
password: staff2

id: staff3
password: staff3

id: test1
password: test1

========================================

Assumption

- Only director can Add and delete user.
- All leave applications final approval are done by director since he is the boss.
- No leave application can be applied by director since director do not have supervisor.
- All records will be kept when a user logout.

========================================

User manual

- Login as director in order to add or delete staff through "User Center" menu.
- director can check the user list through "User Center" -> "Staff List".
- Logout director and login test1.
- test1 apply leave through "Application" -> "New Application".
- Logout test1 and login staff1 since staff1 is the supervisor of test1.
- staff1 can endorse or decline the leave application through "Application" -> "Approval Process".
- Logout staff1 and login director since director is the indirect supervisor for test1.
- director can endorse or decline the leave application through "Application" -> "Approval Process".
- Logout director and login test1 to check application result.
- test1 check her own application status through "Application" ->  "My Application".


Functions

1. New a staff
	a. Input a staff name
	b. Select a supervisor for the new staff
	c. Press "New a staff" button
2. Delete a staff
	a. Select a staff from pull down menu
	b. Press "Delete a staff" button
3. Assign supervisor
	a. Select a staff from pull down menu
	b. Select a supervisor from pull down menu
	c. Press "Assign a supervisor" button 
4. Apply for a leave
	a. Select a staff from pull down menu
	b. Input the start date
	c. Input the end date
	d. Press "Apply for a leave"
	e. Applicant's suppervisor will prompt to endorse or decline for the leave application
	f. After the approval processes, application result will prompt for applicant 
5. Director
	a. Shows director's name and no supervisor

