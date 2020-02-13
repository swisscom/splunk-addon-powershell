# TA-Microsoft-PowerShell
 
* Author: Swisscom CSIRT, Swisscom (Schweiz) AG
* Source: XmlWinEventLog:Microsoft-Windows-PowerShell/Operational
* Has index-time ops: false

# Update History

## 0.2.0 - 2020-02-13

* Update to work with the new Splunk_TA_windows v5 and onwards - https://docs.splunk.com/Documentation/WindowsAddOn/5.0.1/User/Upgrade#Upgrade_from_version_4.8.4_to_version_5.0.1
* All searches,reports and dashboards using `sourcetype="XmlWinEventLog:Microsoft-Windows-PowerShell/Operational"` need to use `source="XmlWinEventLog:Microsoft-Windows-PowerShell/Operational"` instead, due to the upgrade to Splunk_TA_windows v5

## 0.1.0 - 2019-03-01
* Add initial PowerShell event log field extraction
* Tested with PowerShell 5.1

# Using this TA

Configuration: Install TA via GUI on all search heads, install via your preferred method (manual or Deployment Server) on forwarders running on Windows.
