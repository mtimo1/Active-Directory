# 01 installing the Domain Controller
1. Use 1 `sconfig` to:
    - Change the hostname
    - Change th IP address to static
    - change the DNS server to our own ip address

2. Install th Active Directory Windows Feature

```shell
Install-WindowsFeature AD-Domain-Server -IncludeManagementTools
```