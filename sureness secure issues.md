\[NAME OF AFFECTED PRODUCT(S)]: Sureness

\[AFFECTED AND/OR FIXED VERSION(S)]: before version 1.0.8

\[PROBLEM TYPE]:

Vulnerability Type: hard-coded credential

Root Cause: CWE-798, use of hard-coded credentials

\[DESCRIPTION]: Sureness version before 1.0.8 is vulnerable to hard-coded credential vulnerability. In this library, there is a hard-coded secret used to generate and verify the Json Web Token. This vulnerability has been reported that can be exploited to craft arbitrary JWT tokens and subsequently bypass authentication for web-based APIs.

\[Reference]: <https://github.com/dromara/sureness/issues/164>
