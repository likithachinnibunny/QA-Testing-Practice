# Login Page Test Cases

## TC_001 - Valid Login
Steps:
1. Open login page
2. Enter valid username and password
3. Click login

Expected Result:
User should be redirected to dashboard

---

## TC_002 - Invalid Password
Steps:
1. Enter valid username
2. Enter wrong password
3. Click login

Expected Result:
Error message should be displayed

---

## TC_003 - Empty Fields
Steps:
1. Leave username and password blank
2. Click login

Expected Result:
Validation message should appear

---

## TC_004 - Invalid Email Format
Steps:
1. Enter invalid email format
2. Enter password
3. Click login

Expected Result:
Error message for invalid email

---

## TC_005 - Password Masking
Steps:
1. Enter password

Expected Result:
Password should be hidden (****)
