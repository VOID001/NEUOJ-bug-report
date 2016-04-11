NEUOJ
====
GPG Signing Key Enabled, Only Commit with verified GPG Key will be allowed in this repo
__Ver 1.0 Released__ 2.0 Working In Progress

### Function Enabled for v2.0

* [ ] Problem
 * [ ] Problem Database, Training System
 * [ ] Manually define problem difficulty
 * [ ] Add Standard Solution problem for each problem
 * [ ] Use Tag for admin
 * [ ] Give the statistics info of the problem
* [ ] User
 * [ ] Role Control (Use Entrust maybe)
 * [ ] Add friends
 * [ ] Detailed Profile
 * [ ] Admin User managment panel
 * [ ] User can add Teams
 * [ ] Homepage give personized info
  * [ ] Related Problems
  * [ ] Problems working on
  * [ ] Friends activity
* [ ] Submission
 * [ ] Multi Lang Submission Support
 * [ ] SIM for check copied code
 * [ ] A full rejudge system
 * [ ] Wrong Answer Diff
 * [ ] Admin Submission management panel
 * [ ] Multiple testcase ? (Maybe)
* [ ] Contest
 * [ ] Each user can add contest
 * [ ] Contest Announcement(Broadcast?)
 * [ ] Contest BBS
 * [ ] Export Ranklist
 * [ ] Contest Statistics
* [ ] CMS
 * [ ] BBS Function
 * [ ] Blog
* [ ] System & Log
 * [ ] Log System
 * [ ] Admin Dashboard system info panel
* [ ] File Managment
 * [ ] Download Files
 * [ ] Upload Files
 * [ ] Delete Files
 * [ ] Manage Files

### Function Implmented for v1.0 (Done)
* [x] Problem managment
 * [x] Add Problem
 * [x] Edit Problem
 * [x] Delete Problem
 * [x] Edit data
 * [x] Visibility Lock Manual Enable
 * [x] Load in Problem from XML
* [x] Hold Contest
 * [x] Three kind of access to contest: Private Register Public(Ver 2.0)
 * [x] Enable user register himself into the register Contest(Ver 2.0)
 * [x] Board display
 * [ ] Import student info from xls and xlsx etc.(Ver 2.0)
 * [x] Rejudge a Problem by ContestID or Submission ID
 * [x] Balloon System(semi stub)
* [ ] Root Admin Panel
 * [ ] + User Managment
 * [ ] Dashboard Show System Status(Not sure)
* [x] Auth module
 * [x] Register
 * [x] Login
 * [x] Reset Password(Need a mail server)
 * [x] "Future" SSO and Third party login
* [ ] Problem Browsing
 * [x] Search problem by id
 * [x] View Page-splited problem list
 * [ ] Search problem by title
* [x] Problem Submit
* [x] Judge (Current Plan: use domjudge judgedaemon to judge)
 * [x] Read domjudge judge/ code and make the Request Graph
 * [x] Implement the RESTful API with laravel
 * [x] Compile Error Message Return to user
* [ ] RoleCheck (Ver 2.0)
* [ ] Content Managment System (CMS) Use one Plugin

 

### top level route
* /profile User profile page
* /dashboard User managment panel
* /problem Show Problem(s)
* /status Show status(es)
* /auth Authenticate interface (Register login and reset password)
* /contest Show or get in contest
* /discuss Route to subfunction of bbs
* /ajax API handler for Ajax
* /api Judgehost api entry

### Code Styling

Use [PSR-2](http://www.php-fig.org/psr/psr-2/) Code Standard
