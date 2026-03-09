# metasploitable-privilege-escalation
Privilege escalation on Metasploitable 2 lab machine

# Metasploitable Privilege Escalation

## Initial Access
SSH login with user: msfadmin

## Enumeration
Command used:

sudo -l

## Vulnerability
User msfadmin is allowed to run ALL commands via sudo.

## Exploitation
Command used to escalate privileges:

sudo su

## Result
Root access obtained.
