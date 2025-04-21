# All-In-One-DNS-Wordlist
This repository provides a comprehensive DNS wordlist containing 20,728,676 unique entries tailored for advanced subdomain enumeration and brute-forcing. Designed for ethical penetration testing and security research, this wordlist aims to uncover subdomains across various domains effectively.

## Features
- Size: 20,728,676 entries of carefully curated subdomain keywords.
- Extensive Coverage: Contains millions of potential subdomains to ensure maximum discovery.
- Versatile Use: Compatible with tools like ffuf, gobuster, Sublist3r, Amass, massdns, dnsx, and more.
- Optimized Performance: Crafted for fast DNS resolution and minimal false positives.
- Regular Updates: Continuously refined to include new patterns and remove duplicates.

## Ideal For
- Bug bounty hunters seeking to enumerate hidden assets.
- Penetration testers performing reconnaissance on large networks.
- Researchers analyzing DNS subdomain patterns.

### Example Usage:
#### Download Command:
```
git clone https://github.com/XploitPoy-777/All-In-One-DNS-Wordlist.git
```
-  Navigate to the Directory:
```
cd All-In-One-DNS-Wordlist
```


- FFUF 
```
ffuf -c -u https://FUZZ.target.com -w /path/to/wordlist.txt -mc 200 -rate 100 -v results.txt
```
-  Gobuster
```
gobuster dns -d target.com -w /path/to/wordlist.txt -t 50
```
- Amass
```
amass enum -active -d target.com -src -ip -brute -w /path/to/wordlist.txt
```

## Totally 
The repository offers one of the largest DNS wordlists for brute-forcing subdomains, catering to penetration testers, bug bounty hunters, and security researchers. It aims to maximize subdomain coverage across domains by combining multiple sources and curated datasets, ensuring both depth and breadth.

## Disclaimer:
- This wordlist is intended for legal security assessments on authorized systems. The misuse of this tool for unauthorized testing may lead to legal consequences.
