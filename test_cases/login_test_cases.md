# Login Test Cases

## TC_001 – Valid Login
Steps:
1. Open login page
2. Enter valid username/password
3. Click login

Expected:
User redirected to dashboard

---

## TC_002 – Invalid Password
Expected:
Error message: Invalid credentials

---

## TC_003 – Empty Fields
Expected:
Validation messages displayed

---

## TC_004 – Password Masking
Expected:
Password hidden

---

## TC_005 – Boundary Test (Min Length)
Input:
Username: 1 char

Expected:
Validation error

---

## TC_006 – SQL Injection
Input:
' OR '1'='1

Expected:
Login fails (secure handling)
