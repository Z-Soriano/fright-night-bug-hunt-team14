# Test Cases: [Your First Name Last Initial]

**Team number:** [14]

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

**Test ID: Z1**
**Written by:Zachary**
**Title: Negative Votes**
**Traces to: castVote(costumeID)**
**Test type:** (Unit / Integration / System / Acceptance / Boundary Value / **Negative** / Security)
**Preconditions: total votes left = 0**
**Test data:**

**Steps:**
1. Click on votes navbar
2. Vote 3 times on any costume (should have 0 votes remaining)
3. Vote one more time to get negative votes left

**Expected result: You have used all of your votes! Number of votes no longer decrements**
**Actual result:**
**Status:** (Pass / **Fail**)
**Severity:** (Critical / **Major** / Minor, Fail only)
**V or V:** (Verification / **Validation**, Fail only)

---

**Test ID: Z2**
**Written by: Zachary**
**Title:Concat vs incrememnt**
**Traces to: store.js**
**Test type: Negative**
**Preconditions: User has votes remaining**
**Test data: Costume Vampire Accountant, inital votes "2"**

**Steps:**
1. Go to votes on navbar
2. vote vampire accountant

**Expected result:  2+1 = 3 or n+1**
**Actual result:, but get 21, 211, 2111... etc**
**Status: Fail**
**Severity: Critical**
**V or V: Validation**

---
