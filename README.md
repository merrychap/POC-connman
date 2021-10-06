### ConnMan

ConnMan is an internet connection manager for embedded devices running the Linux operating system. 

Github - https://github.com/meetecho/janus-gateway

CVE ID | Score | Description
-------|-------|-------------
[CVE-2021-33833](https://nvd.nist.gov/vuln/detail/CVE-2021-33833) | **9.8 CRITICAL** | ConnMan (aka Connection Manager) 1.30 through 1.39 has a stack-based buffer overflow in uncompress in dnsproxy.c via NAME, RDATA, or RDLENGTH (for A or AAAA).