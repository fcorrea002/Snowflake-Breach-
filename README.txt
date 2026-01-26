CS50 Cybersecurity – Final Project
Snowflake Breach 2024 – Credential Compromise in Cloud Environments
Author: Fernando Corrêa da Silva Júnior
GitHub: fcorrea002
edX: fcorrea007
Video Recording Date: [January 9, 2026]
Incident Date: May–June 2024
CVE: Not applicable (credential-based breach)

📌 Project Overview
This project analyzes the Snowflake Breach of 2024, one of the most significant credential-based cloud security incidents of recent years. Attackers gained access to multiple Snowflake customer environments using valid credentials stolen through infostealer malware such as RedLine, Lumma, and Vidar.

No vulnerability inside Snowflake was exploited.
Instead, the incident highlights how weak identity controls, especially the absence of mandatory MFA, can lead to large-scale data compromise.

This project includes:

A full 7–10 minute presentation video
A complete slide deck
A structured technical incident analysis
Mitigation recommendations aligned with course concepts
📌 Why This Topic?
I selected this incident because it aligns directly with key topics in CS50 Cybersecurity, including:

Authentication & Identity
Cloud security principles
Shared responsibility model
Privacy and data protection
Threat analysis and attack vectors
It is also a recent real-world example (within 24 months), meeting project requirements.

📌 Incident Summary
Between May and June 2024, attackers accessed Snowflake customer accounts by leveraging credentials previously harvested by infostealer malware. Many accounts lacked MFA, allowing attackers to authenticate normally and extract large data sets.

Stolen customer data was later advertised for sale on dark web marketplaces.

📌 Key Technical Findings
Attackers used infostealer malware to harvest passwords and authentication tokens.
Several Snowflake accounts had no MFA enabled.
Legacy authentication paths still allowed password-only logins.
No zero-day vulnerability or CVE was involved.
Exfiltration occurred through normal Snowflake query activity.
The incident demonstrates failure in identity hygiene, not platform security.
📌 Recommendations
For Organizations
Enforce mandatory MFA for all cloud platforms
Prevent use of browser-stored credentials
Deploy EDR to detect infostealers
Restrict logins by IP, device, and geolocation
Monitor large data export queries
Implement Zero Trust principles
For Individuals
Avoid storing passwords in browsers
Use password managers
Enable MFA everywhere
Keep personal devices separate from corporate access
Use hardware authentication tokens
📌 Files Included in This Repository
	• / ├── README.md - This file
├── slides/
│ └── slides_CS50 - (FinalProject - Snowflake Breach 2024_Presentation.pptx)
├── report/
│ └── CS50 Cybersecurity (Final Project – Snowflake Breach (May-Jun 2024).pdf)
├── script/
│ └── Full narration (script - Snowflake Breach 2024.txt)
└── video/
└── video_link - Snowflake Breach 2024.txt
📌 How to View the Video
The video has been uploaded to YouTube as Unlisted, as required.
Link: [https://youtu.be/YdYP3nlHVz4]

📌 Concluding Remarks
The Snowflake 2024 breach is a powerful example of how authentication weaknesses, not software vulnerabilities, remain one of the most exploitable attack surfaces in cloud environments.

This project demonstrates how a preventable identity compromise escalated into a large-scale data breach affecting multiple organizations.

📌 License
This project is submitted as part of CS50's Introduction to Cybersecurity (HarvardX).
YouTube video is unlisted per course policy.

Materials may not be redistributed without permission.
