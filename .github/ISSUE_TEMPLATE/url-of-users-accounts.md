---
name: URL of Users accounts
about: User account switches to a different user by changing the URL
title: BUG
labels: bug, documentation
assignees: ava111s

---

**Describe the bug**
User logs into their own account. However once logged in changes the URL link from his own ID 1 to a different number then the site should be broken or unavailable. 
During the log in stages it should take user to his own account. however, if the URL number is changed from useraccount1 to user account 10 then user logs into someone else account.

**To Reproduce**
Steps to reproduce the behaviour:
1. Get user to sign in  
2. once logged into user account
3. Then the user will be given a unique url
4.  If the url is in ascending order then user changes the url to a different number
5. user should not have access to somebody elses account.

**Expected behaviour**
So, If the user has put somebody else's unique URL then the website should crash, link should be unavailable without logging in and should get the user to sign in to that account.

**Screenshots**
N/A

**Desktop (please complete the following information):**
HP Pavillion
Window 8

**Additional context**
Security issue relating to URL
