\[NAME OF AFFECTED PRODUCT(S)]: lamp-cloud

\[AFFECTED AND/OR FIXED VERSION(S)]: before version 3.8.1

\[PROBLEM TYPE]:

Vulnerability Type: hard-coded credential

Root Cause: CWE-798, use of hard-coded credentials

\[DESCRIPTION]:

&#x20;lamp-cloud version before 3.8.1 is vulnerable to hard-coded credential vulnerability. In this library, there is a hard-coded secret used to generate and verify the Json Web Token. This vulnerability has been reported that can be exploited to craft arbitrary JWT tokens and subsequently bypass authentication for web-based APIs.

\[Reference]: [Using predictable/constant cryptographic key when creating and verifing Json Web Token. · Issue #183 · dromara/lamp-cloud (github.com)](https://github.com/dromara/lamp-cloud/issues/183)
