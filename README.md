# Reconnaissance
<details>

<summary>Tools</summary>

```console
:~$ * DNSdumpster - for DNS ips
    * netcraft - for finding top lvl domain n subdomain gps os whois
    * dig and sublist3 - to find subdomains
    * GHDB - gui and Searchsploit CLI
    * Shodan,Censys,zoomeye - detect device and nw with vulnerabilty also finds os
    * meta search engine - gather info from other search engine and make their own result
    * FTP search engine - NAPALM FTP , Freeware web ftp file , mamont and globalfilesearch.com
    * archive.org and photon for linux - archive version of website
    * Spokeo - people search service
    * Recon-ng - powerfull tool for website recon
    * theHarvester - for enumerate linkdin 
    * BuzzSumo - analyzing target social media presence
    * Sherlock - to search in social nw sites
    * whois.domaintools.com - for get whois details like domain owner and nameserver etc
    * tineye - for reverse image search engine
    * TheHarvester - for harvesting subdomains and email address 
```
    
<summary>DNS enumeration tools</summary>

    ```console
    :~$  * SecurityTrails - DNS enum
         * Fierce - DNS enum
         * DNSrecon for AI

         Reverse DNS enum
         * DNSrecon (ip)
         * mxtoolbox - reverse lookup
    ```
<summary>to locate the network range</summary>

```console
:~$ * ARIN - whois details and network range 
    * traceroute - hop
    * tracert - for windows
```
traceroute tools
```console
:~$ * netscantools pro - suite application
    * pingPlotter
```
email tracking tool

```console
:~$ * emailtrackerpro - scans by email header
    * IP2location
```
footprinting tools

```console
:~$ * Maltego 
    * recon-ng
    * FOCA - to get meta data of hidden info in doc
    * SUBfinder - to find subdomain
    * Recon-Dog - all in one for basic info
    * Billcipher - Information Gathering tool for a Website or IP address
```
</details>

# Scanning network

<details>
<summary>tools</summary>

```console
:~$ * nmap - to scan network
    * zenmap - gui version of nmap
```
to find os
```console
:~$ * unicornscan
```
ip spoofing
```console
:~$ * Hping3 
```
to create custom packets
```console
:~$ * colasoft packet builder
    * netscan tools pro
```
proxy tools
```console
:~$ * proxy switcher
    * cyber ghost vpn
```
anonymizer
```console
:~$ * whoinix
    * tails - live os

```
scanning detection and prevention tools
```console
:~$ * ExtraHop
    * Splunk
```
</details>

# Enumeration

<details>
<summary>netbios tools</summary>

```console
:~$ * nbtstat - utility
    * NetBIOS enumerator - gui tool
    * nmap - script>nbtstat.nse
```
</details>
<details>
<summary>SNMP enumeration tool</summary>

```console
:~$ * OPUtils
    * Network performance monitor
    * SNMPWalk
    * Nmap - script > snmp-processes 
    * SNMP-check
    * SoftPerfect Network Scanner 
```
</details>

<details>

<summary>LDAP enumeration tools</summary>

```console
:~$ * Softerra LDAP administrator
    * ldapsearch
```
</details>
<details>

<summary>NTP enumeration tools</summary>

```console
:~$ * PRTG Network monitor
```
NFS enumeration
```console
:~$ * rpcinfo - to get ip adrr for an open nfs port
    * showmount 
    * RPCScan
    * Superenum
```
</details>
<details>
<summary>SMTP enumeration tools</summary>

```console
:~$ * utilities : telnet and netcat
    * nmap - script
    * metasploit
    * NetscanTools pro
    * smtp-user-enum - cli
```
</details>
<details>
<summary>DNS enumeration using DNS zone transfer</summary>

```console
:~$ * dig <domain of name server> <target domain> axfr
    * nslookup - by setting set querytype=soa >>>/ls -d <domain of name server>
    * DNS recon - axfn
```
dns cashe snooping
```console
:~$ * dig - recurisive and non recursive
```
dnssec zone walking
```console
:~$ * LDNS
    * DNSRecon
    * owasp Amass
    * nmap
```
</details>
<details>

<summary>other enumeration and tools</summary>

```console
:~$ * IPSEC - nmap -sU -p 500 <ip>
    * Voip enumeration - svmap
```
</details>

# Vulnerability analysis

<details>
<summary>vulnerabilty and network automatred scanner</summary>

```console
:~$ * NESSUS
    * Qualys
    * GFI lannGuard
    * NIKTO
```
</details>