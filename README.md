# CVE-2023-32314
vm2 is a library that provides a sandbox created to run code without worry about the security for the machine which will actually run the code.
It abuses an unexpected creation of a host object based on the specification of `Proxy`. A hacker can bypass the sandbox protections to gain remote code execution rights on the host actually running the code. This vulnerability was patched in the release of version 3.9.18 of vm2.

Find the poc in exploit.js

# How to solve it
Run this command:
```
npm update vm2
```

DON'T USE THIS EXPLOIT TO HACK ANY SITE USING vm2 WITHOUT PERMISSION, REMEMBER HACKING IS ILLEGAL AND THE AUTHOR IS NOT RESPONSIBLE FOR ANY MALICIOUS USE OF THIS EXPLOIT

# Credit
https://nvd.nist.gov/vuln/detail/CVE-2023-32314
