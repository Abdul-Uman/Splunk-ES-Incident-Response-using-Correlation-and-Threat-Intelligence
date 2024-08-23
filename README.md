# Splunk ES Incident Response using Correlation and Threat Intelligence

## Overview

This repository provides a step-by-step guide on using **Splunk Enterprise Security (ES)** for effective incident response. It includes detailed instructions on setting up correlation searches, integrating threat intelligence tools, and responding to security incidents. This guide is tailored for security analysts, SOC teams, and anyone looking to enhance their security monitoring with Splunk ES.

## Table of Contents

- [Introduction](#introduction)
- [Installation and Integration](#installation-and-integration)
- [Incident Response Examples](#incident-response-examples)
  - [Large Number of Windows Login Failure Attempts Detected](#large-number-of-windows-login-failure-attempts-detected)
  - [High Number of Deny Events from the Same Source - Inbound](#high-number-of-deny-events-from-the-same-source-inbound)
- [Threat Intelligence Integration](#threat-intelligence-integration)
  - [Integrating Threat Intelligence Tools with Splunk ES](#integrating-threat-intelligence-tools-with-splunk-es)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## Introduction

In today’s security landscape, the ability to quickly detect, analyze, and respond to threats is crucial. This repository showcases how **Splunk Enterprise Security (ES)** can be leveraged to create powerful correlation searches and integrate with leading threat intelligence platforms. By following the steps outlined here, you will be able to improve your organization's incident detection and response capabilities using Splunk ES.

## Installation and Integration



### Integrating Threat Intelligence Tools with Splunk ES

1. **Cisco Talos Intelligence**:
   - Configure the Cisco Talos feed by integrating it with your Splunk ES environment. Use the available API or download threat intelligence files and set them up as lookup tables.

2. **MXToolbox**:
   - Set up MXToolbox lookups in Splunk ES for email and network diagnostics. Utilize MXToolbox's API to automate lookups or manually add tools into your workflow.

3. **IPVoid**:
   - Integrate IPVoid with Splunk ES by setting up automated lookups for malicious IP addresses. Add IPVoid to your threat intelligence sources in Splunk.

4. **WhoisDomainTools.com**:
   - Use WhoisDomainTools.com to gather detailed information on domains and IPs. Integrate the lookups in Splunk ES by creating custom commands or utilizing existing integrations.

5. **VirusTotal**:
   - Integrate VirusTotal's threat intelligence feed into Splunk ES. Automate file and URL scanning, and use the results to enrich your Splunk ES incidents.
