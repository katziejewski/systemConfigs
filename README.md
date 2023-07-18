# systemConfigs
Various system configurations to be pulled by automation tooling


Log Forwarding:
- Rsyslog configs to forward all standard logging to a syslog server
- Forward relevant Zeek logs to a syslog server
  Sysinternals Sysmon will also be in use, but doesn't require particular configs
    - This may be changed later and a dedicated agent used for collection

Sysmon Configuration - Currently just stealing SwiftOnSecurity's Linux Sysmon config since frankly it's better than what I came up with

Zeek Configuration - Stock Zeek config, just setting interface name
