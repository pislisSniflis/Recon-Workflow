# Recon Workflow Guide

This guide provides a structured approach to reconnaissance using key tools and resources. Follow the steps below to ensure thorough information gathering.

## Key Tools Summary

| **Task**                   | **Tool/Resource**                    |
|----------------------------|---------------------------------------|
| Subdomain Enumeration      | Amass, Sublist3r                     |
| Port Scanning              | Nmap, Masscan                        |
| DNS Recon                  | DNSDumpster, nslookup, dig           |
| OSINT                      | Google Dorks, LinkedIn, Hunter.io    |
| Service Enumeration        | Nmap scripts, Nikto                  |
| Technology Identification  | WhatWeb, Wappalyzer                  |
| Sensitive File Discovery   | Wayback Machine, Common Crawl        |

## Workflow Steps

1. **Subdomain Enumeration**  
   - Use **Amass** or **Sublist3r** to discover subdomains of the target domain.
   - Document all findings for further analysis.

2. **Port Scanning**  
   - Perform a fast scan using **Masscan** to identify open ports quickly.
   - Follow up with **Nmap** for detailed port and service information.

3. **DNS Recon**  
   - Use **DNSDumpster** for a visual representation of DNS records.
   - Verify DNS entries using **nslookup** and **dig**.

4. **OSINT (Open Source Intelligence)**  
   - Conduct searches with **Google Dorks** to uncover publicly available information.
   - Explore professional profiles on **LinkedIn** and check emails with **Hunter.io**.

5. **Service Enumeration**  
   - Leverage **Nmap scripts** and **Nikto** to enumerate services running on identified ports.
   - Look for misconfigurations or vulnerabilities.

6. **Technology Identification**  
   - Identify the technologies used by the target using **WhatWeb** and **Wappalyzer**.
   - Focus on web servers, CMS, and frameworks for potential exploitation.

7. **Sensitive File Discovery**  
   - Use the **Wayback Machine** to review historical versions of the target’s website.
   - Crawl public data with **Common Crawl** to locate sensitive files or directories.

## Notes and Best Practices
- Always document your findings at each step for easy reference.
- Respect ethical guidelines and legal boundaries during reconnaissance.
- Prioritize tasks based on the target's scope and objectives.

By following this workflow, you can efficiently gather actionable intelligence on your target.