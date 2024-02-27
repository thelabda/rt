
- Spoofy is a program that checks if a list of domains can be spoofed based on SPF and DMARC records. You may be asking, "Why do we need another tool that can check if a domain can be spoofed?"#

https://github.com/MattKeeley/Spoofy

python3 spoofy.py -d <DOMAIN> -o stdout

####################

- NameHash Creating a user name list for brute force attacks.#


Invoke-UsernameHarvestOWA -ExchHostname <TARGET> -Domain <DOMAIN> -UserList <users.lst> -OutFile <output.txt>

https://gist.github.com/superkojiman/11076951

####################

- Seatbelt is a C# tool which automatically collects enumeration data for a host.  It can check for security configurations such as OS info, AV, AppLocker, LAPS, PowerShell logging, audit policies, .NET versions, firewall rules, and more
https://github.com/GhostPack/Seatbelt

C:\Tools\Seatbelt\Seatbelt\bin\Release\Seatbelt.exe -group=system

####################

- Symantec Sitereview
https://sitereview.bluecoat.com/#/

####################

 - Chameleon is a tool which assists red teams in categorising their infrastructure under arbitrary categories. Currently, the tool supports arbitrary categorisation for Bluecoat, McAfee Trustedsource and IBM X-Force. However, the tool is designed in such a way that additional proxies can be added with ease.

https://github.com/mdsecactivebreach/Chameleon

usage: chameleon.py [-h] [--proxy <proxy>] [--check] [--submit]
                    [--domain <domain>]
