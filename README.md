# Reconnaissance

BUG BOUNTY BOOTCAMP BOOK!

1.Google Dorking

2.Scope Discovery

1.WHOIS and Reverse WHOIS

[https://viewdns.info/reversewhois/](https://viewdns.info/reversewhois/)

[https://viewdns.info/reverseip/](https://viewdns.info/reverseip/)

whois -h [whois.cymru.com](http://whois.cymru.com/) 157.240.2.20

2.nslookup

nslookup [facebook.com](http://facebook.com/)

3.Certificate Parsing

1.[crt.sh](http://crt.sh/) 

2.[cencys.io](https://censys.io/)

3.Subdomain Enumeration

Sublist3r,SubBrute, Amass, and Gobuster

**EyeWitness** ([https://github.com/FortyNorthSecurity/EyeWitness/](https://github.com/FortyNorthSecurity/EyeWitness/)) and **Snapper**
([https://github.com/dxa4481/Snapper/](https://github.com/dxa4481/Snapper/)) grab screenshots of a list of URLs.
They can be used to quickly scan for interesting pages among a list of
enumerated paths.

**Wordlist**

[https://github.com/assetnote/commonspeak2](https://github.com/assetnote/commonspeak2)

4.Service Enumeration

1.nmap as active

version

nmap [scanme.nmap.org](http://scanme.nmap.org/) -sV

2.shodan as passive 

5.Directory Brute-Forcing

Dirsearch or Gobuster or ffuf

6.Spidering the Site

burp or zap

7.Third-Party Hosting

site:s3.amazonaws.com COMPANY_NAME

site:amazonaws.com COMPANY_NAME

amazonaws s3 COMPANY_NAME
amazonaws bucket COMPANY_NAME
amazonaws COMPANY_NAME

s3 COMPANY_NAME

pip install awscli

aws s3 cp s3://BUCKET_NAME/FILE_NAME/path/to/local/directory

aws s3 ls s3://BUCKET_NAME/

[https://buckets.grayhatwarfare.com/](https://buckets.grayhatwarfare.com/)

A Ruby script to bruteforce for AWS s3 buckets using different permutations.****

[https://github.com/nahamsec/lazys3/](https://github.com/nahamsec/lazys3/)

8.GitHub Recon

Way to Use Kind of Apis

[https://github.com/streaak/keyhacks/](https://github.com/streaak/keyhacks/)

—

[https://github.com/trufflesecurity/truffleHog/](https://github.com/trufflesecurity/truffleHog/)

[https://github.com/michenriksen/gitrob/](https://github.com/michenriksen/gitrob/)

9.WayBack Machine

[https://archive.org/web/](https://archive.org/web/)

[https://github.com/tomnomnom/waybackurls/](https://github.com/tomnomnom/waybackurls/)
