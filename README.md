# *Simple Administration PowerShell Scripts*
## Script: Remote Netstat Check Script

**Description:**
A simple remote netstat check script that pulls port established data for all servers listed in serverlist.txt at one time.

**Customizable:**
```powershell
$InputFile = ".\serverlist.txt"
$OutputFile = "C:\temp\NetworkPortReport.csv"
```
- $InputFile = ".\serverlist.txt": Adjust $inputFile to serverlist.txt location.
- $OutputFile = "C:\temp\NetworkPortReport.csv": Adjust $outputFile to desired output location

- .\serverlist.txt: Update serverlist.txt and list each host name or IP address within their own line (no header).

**Example:**
```plaintext
server01
server02
172.0.0.1
172.0.0.2
```

---

**Output:** .CSV table format of the results.
