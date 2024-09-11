# PHP CGI RCE (CVE-2024-4577) Scanner

> Just a tool for educational purposes. No legal responsibility.

Scanning CVE-2024-4577 vulnerability with a url list.

Not only sending exploit, but also checking PHP version and whether php-cgi 
exists. Make it more informative to know why (or why not) exploit success.

## Usage

```bash
# install dependencies
pip install -r requirements.txt
# write urls to urls.txt
vim urls.txt
# run scanner
python3 scanner.py
```