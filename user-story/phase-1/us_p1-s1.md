\[ KenSaku Project ]

USER STORIES

PHASE 1 - BASIC CORE FEATURES
# **SPRINT 1 - AUTHENTICATION**
(2025/1/3 - now)

### **#1.1.1 - Sign Up**
**User story:**
As an unauthenticated user,
I want to sign up for KenSaku (with display name, email, password and confirm password), so that I can have an account. 
 
**Acceptance criteria:**
1. Display name: 1-50 characters, contains only (upper/lower) alphabet characters  and numbers.
2. Email: is unique, must pass the HTML native email validation.
3. Password: 8-50 characters, must contain at least one upper letter, one lower letter, one special character and one number.
4. Confirm new password: must match the New password

### **#1.1.2 - Sign In**
**User story:**
As an unauthenticated user,
I want to sign in to my account (with email and password),
so that I can use the features available to authenticated user. 

**Acceptance criteria:**
1. Email: must match the account email.
2. Password: must match the account password.

### **#1.1.3 - Sign Out**
**User story:**
As an authenticated user,
I want to sign out of my account,
so that I can sign up with another account. 

### **#1.1.4 - Change Password**
**User story:**
As an authenticated user,
I want to change my account password (with current password, new password, confirm new password),
so that I can keep my account secure.

**Acceptance criteria:**
1. Current password: must match the account password.
2. New password: 8-50 characters, must contain at least one upper letter, one lower letter, one special character and one number.
3. Confirm new password: must match the New password

### **#1.1.5 - Reset Password**
**User story:**
As user who forgot their password,
I want to reset my account password (with email, new password, confirm new password),
so that I can sign in to KenSaku with new password.

**Acceptance criteria:**
1. Email: must match the account email.
2. New password: 8-50 characters, must contain at least one upper letter, one lower letter, one special character and one number.
3. Confirm new password: must match the New password
