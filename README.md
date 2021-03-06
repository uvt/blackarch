BlackArch
=========

To make use of the pentest set of tools available in the BlackArch toolset please add the BlackArch repository to `/etc/pacman.conf`


```
[blackarch]
SigLevel = Optional TrustAll
Server = http://www.blackarch.org/pub/blackarch/$arch
```

Package Groups
--------------

To see all available packages follow http://www.blackarch.org/packages.html and install any tool individually.  For quicker installs leverage the package groups:

#### Exploitation

```
$ pacman -S blackarch-exploitation
```
- Included packages:
  - beef
  - fern-wifi-cracker
  - fimap
  - metasploit
  - reaver-wps
  - set
  - sqlmap
  - sqlninja
  - websploit
  - xsser

#### Forensics

```
$ pacman -S blackarch-forensics
```

- Included packages:
  - pdf-parser
  - pdfid
  - peepdf
  - volatility

#### Intelligence Gathering

```
$ pacman -S blackarch-intel
```

- Included packages:
  - blindelephant
  - burpsuite
  - cms-explorer
  - dnsbf
  - dnsenum
  - dnsmap
  - hashid
  - netglub
  - nikto
  - snmpcheck
  - ssldump
  - theharvester
  - zaproxy

#### Miscellaneous

```
$ pacman -S blackarch-misc
```

- Included packages:
  - artillery
  - geoipgen

#### Post-Exploitation

```
$ pacman -S blackarch-post
```

- Included packages:
  - chownat
  - netcommander
  - pwnat
  - sslstrip

#### Threat Modeling

```
$ pacman -S blackarch-threat-model
```

- Included packages:
  - magictree

#### Vulnerability Analysis

```
$ pacman -S blackarch-analysis
```

- Included packages:
  - edb
  - fang
  - pentbox
  - scapy
  - sipvicious
  - slowhttptest
  - sslscan
  - tcpjunk

To learn more about each package visit http://www.blackarch.org/packages.html
