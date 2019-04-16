# Splunk Add-on for PowerShell

The Splunk Add-on for PowerShell provides field extraction for PowerShell event
logs. Unfortunately, PowerShell logs are in system language which requires field 
extraction for each language. Furthermore, delimiters are sometimes `:` and sometimes `=`.

Currently supported languages are
* English
* French
* Italien
* German

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
