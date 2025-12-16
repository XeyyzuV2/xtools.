# Bug Bounty Quick Reference

## Recon Phase
```bash
python main.py subnum example.com
python main.py dnsrecon example.com --axfr
python main.py takeover @subdomains.txt
```

## Scanning Phase
```bash
python main.py techscan http://target.com
python main.py wafdetect http://target.com
python main.py headers http://target.com
python main.py sslscan https://target.com
```

## Vulnerability Testing

### Injection
```bash
python main.py xss "http://t.com?q=test" --dom
python main.py ssti "http://t.com?name=x" --deep
python main.py nosql "http://t.com?id=x"
python main.py cmdi "http://t.com?cmd=x" --os linux
python main.py xxe http://api.com --method POST
```

### Access Control
```bash
python main.py cors http://target.com
python main.py ssrf "http://t.com?url=x"
python main.py lfi "http://t.com?file=x"
python main.py redirect http://target.com
```

### API Testing
```bash
python main.py graphql http://api.com/graphql --introspection
python main.py apifuzz "http://api?q=FUZZ" -p sqli --blind
python main.py jwt <token> --crack
```

### Advanced
```bash
python main.py smuggling http://target.com
python main.py cachepoisoning http://target.com
python main.py racecondition http://api/endpoint --threads 50
python main.py deserialize http://target.com --param data
python main.py prototype http://app.com --method POST
python main.py websocket ws://target.com/ws --fuzz
```

## Report
```bash
python main.py report http://target.com --format html
```
