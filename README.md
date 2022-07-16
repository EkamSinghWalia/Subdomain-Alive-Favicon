# Subdomain-Alive-Favicon

Python tool to -Enumerate subdomain of given domain.
-Check alive Domains. -Get Favicon hash.

    
## Deployment

To deploy this script run

```bash
  python3 subfav.py -h domain.tld
```


## Features

1)Enumerate Subdomains and store it in subdomains.txt

2)Check for alive domains having status code 200 and store it in alive.txt

3)Generate Favicon Hash of each domain and store it in favhash.txt


## Prerequisites

1) Subfinder
```bash
  go install -v github.com/projectdiscovery/subfinder/v2/cmd/subfinder@latest
```
2) Python3 
```bash
  apt install python3
```



