# XTOOLS API Documentation v2.4

## Module Structure

Each attack module follows this pattern:

```python
def get_parser_args(parser):
    """Add module-specific arguments to the parser."""
    parser.add_argument('target', help='Target description')

def run(args, console):
    """Main execution function."""
    return {"result": "data"}
```

## Available Modules (73)

### Bug Bounty (26)
xss, ssrf, ssti, sqli, xxe, lfi, idor, cors, jwt, redirect, crlf, clickjack, headers, params, takeover, smuggling, cachepoisoning, racecondition, deserialize, hosthead, bucketscan, jssecrets, wpscan, blindxss, oauth, ssrfchain

### Advanced (13)
graphql, nosql, cmdi, prototype, websocket, vulnscan, wafdetect, sslscan, apifuzz, bruteforce, masscan, wafbypass, zeroday

### Exploit Tools (4)
revshell, obfuscate, genpayload, dnsrebind

### Scanners (8)
portscan, subnum, dirscan, apiscan, techscan, report, wordgen, subfuzz

### DDoS (10)
http, http2, api_stress, slowloris, rudy, udp, syn, tcp_ack, icmp, samp

### Amplification (7)
dns, ntp, memcached, ssdp, snmp, ldap, chargen

### Recon (5)
whois, ipinfo, dnsrecon, proxyfetch, health_check

## Shell Commands

```bash
(XTOOLS) > set target http://example.com
(XTOOLS) > run xss
(XTOOLS) > quick ssrf http://target.com
(XTOOLS) > tools
(XTOOLS) > man graphql
```

---
**XTOOLS v2.4 By XeyyzuV2**
