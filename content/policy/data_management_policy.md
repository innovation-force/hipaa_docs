+++
date = "2016-02-28T08:16:30-08:00"
draft = true
title = "Data Management Policy"
comments = true
share = false
noauthor = true
+++

Innovation Force has procedures to create and maintain retrievable exact copies of electronic protected health information (ePHI) stored in conjunction with Innovation Force Add-ons and for PaaS Customers utilizing our Backup Service. This policy, and associated procedures for testing and restoring from backup data, do not apply to PaaS Customers that do not choose Innovation Force Backup Service. The policy and procedures will assure that complete, accurate, retrievable, and tested backups are available for all systems used by Innovation Force.

Data backup is an important part of the day-to-day operations of Innovation Force. To protect the confidentiality, integrity, and availability of ePHI, both for Innovation Force and Innovation Force Customers, completes backups are done daily to assure that data remains available when it needed and in case of disaster.

Violation of this policy and its procedures by workforce members may result in corrective disciplinary action, up to and including termination of employment.

## Applicable Standards from the HITRUST Common Security Framework

* 01.v - Information Access Restriction

## Applicable Standards from the HIPAA Security Rule

* 164.308(a)(7)(ii)(A) - Data Backup Plan
* 164.310(d)(2)(iii) - Accountability
* 164.310(d)(2)(iv) - Data Backup and Storage

## Backup Policy and Procedures

1. Perform daily snapshot backups of all systems that process, store, or transmit ePHI for Innovation Force Customers, including PaaS Customers that utilize the Innovation Force Backup Service
2. Innovation Force Ops Team, lead by VP of Engineering, is designated to be in charge of backups.
3. Dev Ops Team members are trained and assigned assigned to complete backups and manage the backup media.
4. Document backups
	* Name of the system
	* Date & time of backup
	* Where backup stored (or to whom it was provided)
5. Securely encrypt stored backups in a manner that protects them from loss or environmental damage.
6. Test backups and document that files have been completely and accurately restored from the backup media.
