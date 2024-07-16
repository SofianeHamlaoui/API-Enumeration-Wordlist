# API Enumeration Wordlist
Welcome to the API Enumeration Wordlist project! This repository contains a comprehensive wordlist designed to assist security researchers and penetration testers in discovering endpoints and parameter names within APIs. 
The wordlist is crafted to improve the efficiency and effectiveness of API enumeration during security assessments.

# Overview
API enumeration is a crucial step in identifying potential attack vectors within web applications. 

This wordlist aims to simplify and expedite the process of finding hidden or undocumented API endpoints, parameter names, and values that could be exploited for security vulnerabilities.

# Usage
To use the API Enumeration Wordlist, you can incorporate it into your preferred API enumeration tools, such as:

- [Burp Suite](https://portswigger.net/burp)
- [OWASP ZAP](https://www.zaproxy.org/)
- [FFUF](https://github.com/ffuf/ffuf)
- [Gobuster](https://github.com/OJ/gobuster)
- Custom scripts and tools

Example command using `ffuf`:

```sh
ffuf -u https://example.com/FUZZ -w /path/to/api-wordlist.txt
```
Replace `https://example.com/FUZZ` with the target URL and `/path/to/api-wordlist.txt` with the path to the wordlist file.

# Contributing
We welcome contributions from the community to help improve and expand the wordlist. If you have suggestions or additions, please don't hesitate.
