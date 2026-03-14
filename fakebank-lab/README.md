"To outsmart a hacker, you need to think like one."

Offensive Security is breaking into computer systems, exploiting software bugs, finding loopholes in apps which can lead for unauthorized access. The goal is to access to understand how hacker may think and how can we defense our system.

>> Fake Bank Lab
  >Here we learn about "BRUTE-FORCE ATTACK", which we try to find possible links for hidden web pages in a web app. these can be links that are hidden from the user. To do this we use a tool called "DIRB". Here is the dirb command we write in our terminal to get potential web links.

    >>> dirb http://fakebank.thm (use your link)
![image alt](https://github.com/Schh404/Cyber-Security-Labs/blob/main/DirbCOm.png?raw=true)
  
  >> first part says the URL_BASE we scanned. It also shows the location of the wordlist file used by the tool which contains common page names that will be tested during the brute-force attack. In this case, the tool uses the default wordlist included with the tool, located at /usr/share/dirb/wordlists/common.txt.
