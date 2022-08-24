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
Ring 1 (Insider Team) 79 Devices
Ring 2 (Global Release) 12501 Devices

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
Availability - The service needs to be available 24 x 7 globally 

Response Time - Automated Ring 1 and Ring 2 within a 4 week cycle

Accuracy - The accuracy of the service is essential to ensure our desktop security posture has the least exposure to known vulnerabilities 

# Objectives
Availability - 99.9% availability 24/7

Response Time - 100% of all monthly patches to be targeted to all managed devices

Accuracy - 90% of all patches to be successfully installed within 3 weeks of patch release

# Agreements
Availability - 99% availability 24/7

Response Time - 100% of all monthly patches to be targeted to all managed devices

Accuracy - 90% of all patches to be successfully installed within 3 weeks of patch release

Indicator	SLA
Availability	99%

Response Time	100% automated target deployment by day 6 following patch release

Accuracy	90% with 95% accuracy of original estimate
