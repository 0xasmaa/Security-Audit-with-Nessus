# Network Vulnerability Findings

## Target
  - A Kali Linux VM as the scanning machine
  - A Windows 10 VM as a regular target

## Summary of Vulnerabilities
| Vulnerability            | Severity | Description                      | CVE      | Recommendation                                                                 |
|--------------------------|----------|----------------------------------|--------- |--------------------------------------------------------------------------------|
| SMB Signing Not Required | Medium   | The SMB server allows            | CVE-XXXX | Enable SMB signing on the server or restrict SMB access to trusted networks.   |
|                          |          |   connections without SMB signing,|          |                                                                                |
|                          |          |   making it vulnerable            |          |                                                                                |
|                          |          |   to man-in-the-middle attacks.   |          |                                                                                |

## Risk Assessment
- Critical: 0
- High: 0
- Medium: 1
- Low: 1


