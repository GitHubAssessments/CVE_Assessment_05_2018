# CVE_Assessment_05_2018

This is an assessment of the software SYNC 3.15.89 (Evidence_SYNC_Setup.exe). Initially, was identified a few red flags regarding the timestamp and the size of the raw data. Further analysis revealed the presence of a TLS call back function and connections with suspicious files and websites.  

The main components reviewed in the software included the sync.exe, taskkill.exe, imm32.dll, driver package installers and the msiexec.exe files.

The software was considered malicious and vulnerable to documented attacks techniques such as process injection and query registry. 
