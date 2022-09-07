# Secure Configuration
(Lite)
## Scope
This Policy applies to all Organization owned devices, data and systems, as well as all employees and contractors.

## Secure Configuration Process (CIS 4.1)
Configurations for servers, clients and mobile devices will be secured by applying current CIS benchmark recommendations. When available and appropriate, CIS hardened images or images derived from the CIS build kits can be used as the base image for deployment of new systems. Logging should be configured 

## Network Devices (CIS 4.2)
Network device configurations will be secured by applying current CIS benchmark recommendations. 

## Session Locking (CIS 4.3)
Session locking should be configured where supported. The organization should define time limits that are both within the CIS Controls recommendations, and appropriate for their activities, then apply them to categories of sessions.
    
    Client devices (10 minutes)
    Servers (5 minutes)
    Network devices (5 minutes)
    Mobile devices (2 minutes)
    Online services (15 minutes)

## Server Firewalls (CIS 4.4)
Servers should have firewalls enabled and configured per CIS benchmarks.

## Client Firewalls (CIS 4.5)
Clients should have firewalls enabled and configured per CIS benchmarks.

## Enterprise Software (CIS 4.6)
Ensure that Enterprise Software is regularly patched and updated. CIS advisories should be reviewed regularly to identify advisories for vendors or products the organization uses.

## Default Accounts (CIS 4.7)
Default accounts should not be used. These accounts should have the password changed and be disabled, or if possible, the account completely removed. If neither of those options are available, the account should be renamed and the password changed to a very long (24 characters or more), complex password.