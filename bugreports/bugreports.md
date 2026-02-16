# Bug Reports – Sample Website

> Hinweis: Wenn du heute keinen echten Bug findest, sind diese Beispiele trotzdem ok.
> Später ersetzen wir sie durch echte Bugs von einer Website, die du testest.

---

## BR-001: Login button does nothing after clicking

**Priority:** High  
**Severity:** Major  

### Environment
- OS: Windows 10
- Browser: Chrome (latest)
- URL: [add URL here]

### Steps to Reproduce
1. Go to the login page
2. Enter a valid email
3. Enter a valid password
4. Click the "Login" button

### Expected Result
User is logged in and redirected to dashboard.

### Actual Result
Nothing happens after clicking the button. User stays on login page.

### Notes / Evidence
- No error message shown.
- Add screenshot/video if available.

---

## BR-002: Error message missing for invalid password

**Priority:** Medium  
**Severity:** Minor  

### Environment
- OS: Windows 10
- Browser: Chrome (latest)
- URL: [add URL here]

### Steps to Reproduce
1. Go to the login page
2. Enter a valid email
3. Enter an invalid password
4. Click "Login"

### Expected Result
An error message should appear: "Invalid credentials".

### Actual Result
Page reloads but no error message is displayed.

### Notes / Evidence
- User does not know what went wrong.
