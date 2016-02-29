+++
date = "2016-02-28T08:10:41-08:00"
draft = true
title = "Configuration Management Policy"
comments = true
share = false
noauthor = true
+++

Innovation Force standardizes and automates configuration management through the use of Salt scripts as well as documentation of all changes to production systems and networks. Salt automatically configures all Innovation Force systems according to established and tested policies, and is used as part of our Disaster Recovery plan and process.

## Applicable Standards from the HITRUST Common Security Framework

* 06 - Configuration Management

## Applicable Standards from the HIPAA Security Rule

* 164.310(a)(2)(iii) Access Control & Validation Procedures

## Configuration Management

1. Salt is used to standardize and automate configuration management.
2. OSSEC is used to scan systems every 2 hours and on reboot. These scans capture file system changes and also unauthorized or malicious software.
3. No systems are deployed into Innovation Force environments without approval of the Innovation Force CTO.
4. All changes to production systems, network devices, and firewalls are approved by the Innovation Force CTO before they are implemented to assure they comply with business and security requirements. Additionally, all changes are tested before they are implemented in production. All changes are documented using Google forms. Implementation of approved changes are only performed by authorized personnel.
5. An up-to-date inventory of systems is maintained using Google spreadsheets and architecture diagrams hosted on Google Apps and Box. All systems are categorized as production and utility to differentiate based on criticality.
6. Clocks are synchronized across all systems using NTP. Modifying time data on systems is restricted.
7. All front end functionality (developer dashboards and portals) is separated from backend (database and app servers) systems by being deployed on separate servers.
8. All software and systems are tested using unit tests and end to end tests.
9. All committed code is reviewed using pull requests (on Github) to assure software code quality and proactively detect potential security issues in development.
10. Innovation Force utilizes development and staging environments that mirror production to assure proper function.
11. Innovation Force also deploys environments locally using Vagrant to assure functionality before moving to staging or production.
12. Innovation Force schedules production deployments every four weeks.
13. All formal change requests require unique ID and authentication.
14. ClamAV is run on all production hosts for anti-virus protection. Hosts are scanned daily for malicious binaries in critical system paths. The malware signature database is checked hourly and automatically updated if new signatures are available. ClamAV is a part of our Salt-based configuration management and this assures all hosts have anti-virus tools running on them.
15. All physical media is encrypted at provisioning. To verify encryption is consistent and in place for all production storage, checks are performed on a quarterly basis.
