 SQL Injection Demonstration using DVWA

 Objective
The objective of this project is to demonstrate a basic SQL Injection vulnerability using DVWA (Damn Vulnerable Web Application) in low security mode.

 Tools Used
- DVWA
- XAMPP
- MySQL
- PHP
- Browser

 Environment
- Localhost environment using XAMPP
- DVWA security level set to Low

 SQL Injection Payload Used

```sql
1' OR '1'='1
```

 Explanation

The SQL Injection payload modifies the backend SQL query by adding a condition that always evaluates to TRUE.

This allows the application to return unintended database records.

 Steps Performed

1. Installed XAMPP
2. Configured DVWA on localhost
3. Set DVWA security level to Low
4. Opened SQL Injection module
5. Entered SQL Injection payload
6. Observed vulnerable behavior

 Result

The application displayed unintended user data due to improper input validation.

 Conclusion

This project demonstrates how insecure handling of user input can lead to SQL Injection vulnerabilities in web applications.