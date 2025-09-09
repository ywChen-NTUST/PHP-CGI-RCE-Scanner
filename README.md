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
python3 -W ignore exploit.py
```

## Beta Version Usage

If you want it to scan faster, you can try the beta version exploit.

```bash
# install dependencies
pip install -r requirements_beta.txt
# write urls to urls.txt
vim urls.txt
# run scanner
python3 exploit_beta.py
```

If you get an error about the file being opened too many times, you can change the limit to 4096:

```bash
# show the limit
ulimit -n
# change the limit to 4096
ulimit -n 4096
```

