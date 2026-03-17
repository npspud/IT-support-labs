## Problem
User reports internet is connected but websites fail to load.

## Environment
Windows system with manual DNS configuration.

## Steps Taken
- Verified connectivity using 'ping 8.8.8.8' (successful)
- Attempted to reach domain using 'ping google.com' (failed)
- Used 'nslookup google.com' to test DNS resolution
- Identified incorrect DNS server (0.0.0.0)
- Updated DNS settings
- Verified domain connection to google.com (successful)

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
