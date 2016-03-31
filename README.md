# COMP5134
Leave Application system for a Human Resource department, in Java, with GUI

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
