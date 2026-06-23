# FUTURE_CS_01

## Task 1 – Vulnerability Assessment Report for Live Website

### Submitted By

**ERIKALA LOKESH**

### Internship

Cyber Security Internship – Future Interns

---

## Objective

The objective of this project is to perform a vulnerability assessment on a live website using cyber security tools and identify possible vulnerabilities, risks, and remediation steps.

---

## Target Website

testphp.vulnweb.com

---

## Tools Used

* Nmap
* OWASP ZAP
* Browser Developer Tools
* GitHub

---

## Scope of Assessment

This assessment includes:

* Port Scanning
* Service Detection
* Vulnerability Identification
* Risk Analysis
* Security Recommendations

---

## Findings

### 1. Open Ports

* Port 80 (HTTP)
* Port 443 (HTTPS)

**Risk Level:** Low

---

### 2. Missing Security Headers

* Missing X-Frame-Options
* Missing Content-Security-Policy

**Risk Level:** Medium

---

### 3. Cookie Security Issues

* Missing Secure Flag
* Missing HttpOnly Flag

**Risk Level:** High

---

## Recommendations

* Enable HTTPS-only access
* Add security headers
* Configure secure cookies
* Perform regular vulnerability scans

---

## Conclusion

The assessment identified multiple security vulnerabilities related to exposed services, missing security headers, and cookie misconfigurations. Implementing the recommended solutions will improve website security significantly.
