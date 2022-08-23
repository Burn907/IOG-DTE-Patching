# IOG-DTE- Microsoft Windows Patching
Microsoft Windows Operating System feature and security updates for RSG PC's

IOG Desktop Engineering
===================================

# Overview
This service provides Microsoft Windows Feature and Security updates & patching across all ~12.5k pc's within the LNRSG organisation

# Process
Microsoft Windows security updates are released every second Tuesday of every month of the year. Once the updates are released by Microsoft, we utilise Microsoft Windows Update for Business Rings managed by Microsoft EndPoint Manager. Ring 1 (Early Release) is deployed to the Insider team and lab devices for initial testing and feedback. If there are no major compatibility issues reported, the updates are released to Ring 2 (Global Release) on the following Monday. If updates require a reboot, users have up to 3 days until it is forced. During those 3 days, they will be prompted to schedule time of the reboot.

# Feature Requests
Please enter any feature requests into the issues section of this repository.

# Bugs
Please enter any bugs into the issues section of this repository.

# More Information
Ring 1 (Insider Team)
Ring 2 (Global Release)

Delivery Optimisation enabled

# Team
Craig Burnett, Operations Manager
John Sanchez, Senior Systems Engineer
Victoria Gray, Systems Engineer
Anup Bannadi, Systems Engineer
Praveen Chandrashekar, Systems Engineer

# Dependancies
Microsoft timely release of updates.

Microsoft EndPoint Manager aka Intune (Azure services)

# Indicators
Availability - The service needs to be available 24 x 5 globally 

Response Time - Triage is meant to be a quick turnaround time service so proper IPM and engineering resources can be spu nup and scheduled.

Accuracy - The accuracy of the service us important to the Business to enable users to use software for the job and the benefit of the Business

# Objectives
Availability - 99.9% availability 8am - 5pm M-F excluding holidays.

Response Time - 90% of all triage requests will be completed within 3 business days.

Accuracy - 90% of all triaged projects complete within 20% of triage estimation.

# Agreements
Availability - 99% availability 8am - 5pm M-F excluding holidays.

Response Time - 75% of all triage requests will be completed within 5 business days.

Accuracy - 75% of all triaged projects complete within 25% of triage estimation.

Indicator	SLA
Availability	99%
Response Time	75% within 5 bsuiness days
Accuracy	75% with 75% accuracy of original estimate
