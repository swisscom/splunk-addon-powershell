# Splunk Add-on for PowerShell

The Splunk Add-on for PowerShell provides field extraction for PowerShell event
logs.

## Prerequisites

Collection of `Microsoft-Windows-PowerShell/Operational` event logs.

## Installation

Add the folder "ta-microsoft-powershell" to a ZIP and upload it to https://spunkserver/en-US/manager/appinstall/_upload.

## Sourcetypes

Following sourcetype is used for field extraction.

```
sourcetype="XmlWinEventLog:Microsoft-Windows-PowerShell/Operational" 
```

## Changelog

See [changelog in the add-on](ta-microsoft-powershell/README.md).

## Contribution

File an [issue](https://github.com/swisscom/splunk-addon-powershell/issues) or submit a [pull request](https://github.com/swisscom/splunk-addon-powershell/pulls).
