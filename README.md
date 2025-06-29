# Welcome to Our Subdomain Service

This repository manages the list of user projects and subdomains for our platform.

---

## How to Submit Your Project

To get your project listed and assigned a subdomain, please follow these steps:

1. Fork this repository.  
2. Add a JSON file describing your project to the `domains/` folder. Use the following format:

   ```json
   {
     "domain": "yourproject.example.com",
     "repo": "https://github.com/yourusername/yourproject",
     "description": "A short description of your project.",
     "contact": "your.email@example.com",
     "records": {
       "A": "1.2.3.4",
       "CNAME": "target.example.com"
       // NS records are allowed but will be ignored by our DNS setup.
     }
   }
   ```

3. Submit a Pull Request (PR) with your JSON file.

---

## Important Notes

- NS records are allowed in your JSON, but we do not apply NS records in our DNS configuration.  
- Make sure your JSON file is valid and follows the required schema.  
- Our automated checks will validate your submission and may comment on your PR if there are issues.

---

## Resources

- [Pull Request Template](./.github/PULL_REQUEST_TEMPLATE.md)  
- [Issue Templates](./.github/ISSUE_TEMPLATE/)  

---

Thanks for contributing! If you have questions, please open an issue.
