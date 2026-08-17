# Web Server Attack Detection / Web Scanning Detection Using Splunk

## Objective:
The objective of this project is to detect and investigate suspicious web server activity using Splunk.
This project focuses on identifying potential web scanning, directory enumeration, and reconnaissance activity by analyzing HTTP 4xx and 5xx responses.

## Detection
- Identified client IPs generating a high number of HTTP error response
- Analyzed failed requests and unique URIs by client IP
- Identified high-volume client activity for further investigation

## Investigation
- Identify High-Volume Client IPs
- Analyzed Client IP Request Patterns
- Analyze URI Request Patterns

## Investigation Findings
The client IP generated a high volume of requests and HTTP error across multiple web application endpoints. No clear malicious payload or obvious attack pattern was identified from the analyzed URI activity.
