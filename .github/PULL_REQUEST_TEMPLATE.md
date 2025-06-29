## 📦 New Subdomain Request

Thank you for your submission! Please make sure you've followed the guidelines below before submitting your pull request.

---

### 📜 Submission Checklist:

- [ ] I've added my JSON file to the `domains/` folder.
- [ ] My JSON file follows the correct format (see example below).
- [ ] I understand that **NS records are allowed in my JSON but will be ignored during DNS setup**.

---

## 📄 JSON Example:

```json
{
  "domain": "myproject.example.com",
  "repo": "https://github.com/yourusername/yourproject",
  "description": "My awesome project",
  "contact": "yourname@example.com",
  "records": {
    "A": "1.2.3.4",
    "CNAME": "target.example.com"
    // NS records can be listed but will not be applied
  }
}
```

---

## 📌 Notes (optional)

If you have any extra comments or special instructions, add them here:

> _e.g., “Please link to my project’s README in the directory listing.”_

---

✅ Thank you for contributing!
