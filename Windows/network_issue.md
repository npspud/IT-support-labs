## Problem
User reports internet is connected but websites fail to load.

## Environment
Windows system with manual DNS configuration.

## Steps Taken
- Verified connectivity using 'ping 8.8.8.8' (successful)
- Attempted to reach domain using 'ping google.com' (failed)

![](images/network-issue/Attempted_domain.png)

- Used 'nslookup google.com' to test DNS resolution
- Identified incorrect DNS server (0.0.0.0)

![](images/network-issue/nslookup.png)
  
- Updated DNS settings

![](images/network-issue/Updated_settings.png)

- Verified domain connection to google.com (successful)

![](images/network-issue/verify_domain.png)

## Tools Used
- Command Prompt
- ping
- nslookup
- ipconfig

## Resolution
- Updated DNS servers to 8.8.8.8 and 1.1.1.1
- Flushed DNS cache using 'ipconfig /flushdns'

## Outcome
Successfully restored internet functionality by correcting DNS configuration.
