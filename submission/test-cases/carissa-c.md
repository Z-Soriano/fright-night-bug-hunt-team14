# Test Cases: [Your First Name Last Initial]

**Team number:** [XX]

<!--
HOW TO USE THIS FILE
1. Copy this file. Name the copy with your first name and last initial, like  maria-g.md
2. Leave TEMPLATE.md untouched for your teammates.
3. Write at least ONE failing test case. More is better.
4. Copy the block between the lines for each new test case.
5. Test IDs: use your initials plus a number, like  MG-01, MG-02. This keeps IDs unique across your team.
6. See docs/TESTING_FIELD_GUIDE.md for the sample test case TC-00.
-->

---

**Test ID: CC-01**
**Written by: Carissa Chen**
**Title: registering an account with a password of less than 8 characters**
**Traces to: REQ-01**
**Test type: System** (Unit / Integration / System / Acceptance / Boundary Value / Negative / Security)
**Preconditions: be on the log in/register page**
**Test data: username: c, password: aaaa**

**Steps:**
**1. opened the link of the app in my browser**
**2. clicked on the log in/register button**
**3. entered manual test into the register account area**

**Expected result: "password is too short"**
**Actual result: "account created! you can log in now."**
**Status: Fail** (Pass / Fail)
**Severity: Major** (Critical / Major / Minor, Fail only)
**V or V: Verification** (Verification / Validation, Fail only)  

---

**Test ID: CC-02**
**Written by: Carissa Chen**
**Title: submitting multiple customes to the contest**
**Traces to: REQ-03**
**Test type: System/Negative**
**Preconditions: be on the submit costume page, press submit costume button. do it more than once**
**Test data: submitted two of the same customes**
**Steps:**
**1. opened the link of the app in my browser**
**2. clicked on the submit costume button**
**3. clicked on the submit costume button at the bottom**
**4. repeat steps 2 and 3**

**Expected result: "sorry, you've already submitted a costume"**
**Actual result: "costume submitted. good luck!**
**Status: Fail**
**Severity: Critical**
**V or V: Verification**

---


**Test ID: CC-03**
**Written by: Carissa Chen**
**Title: only the owner of a submission should be able to delete it**
**Traces to: REQ-08**
**Test type: Security**
**Preconditions: have submitted costumes in the gallery already, and an account that's logged in when you try to delete it**
**Test data: logged in and be able to delete any other gallery submission**

**Steps:**
**1. log in as another user**
**2. go to the gallery, find another user's costume**
**3. delete another user's costume**

**Expected result: either not even have a delete button option available to submissions that aren't yours, or say "unable to delete a custome that isn't yours"**
**Actual result: "costume deleted."**
**Status: Fail**
**Severity: Critical**
**V or V: Verification**

---