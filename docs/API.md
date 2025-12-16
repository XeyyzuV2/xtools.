# XTOOLS API Documentation v2.2

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

## Available Modules (54)

### Bug Bounty (17)
xss, ssrf, ssti, xxe, lfi, cors, jwt, redirect, crlf, clickjack, headers, params, takeover, smuggling, cachepoisoning, racecondition, deserialize

### Advanced (9)
graphql, nosql, cmdi, prototype, websocket, vulnscan, wafdetect, sslscan, apifuzz

### DDoS (9)
http, http2, slowloris, rudy, udp, syn, tcp_ack, icmp, samp

### Amplification (7)
dns, ntp, memcached, ssdp, snmp, ldap, chargen

### Scanners (6)
portscan, subnum, dirscan, apiscan, techscan, report

### Recon (6)
whois, ipinfo, dnsrecon, proxyfetch, health_check, genpayload

## Shell Commands

```bash
(XTOOLS) > set target http://example.com
(XTOOLS) > run xss
(XTOOLS) > quick ssrf http://target.com
(XTOOLS) > tools
(XTOOLS) > man graphql
```

---
**XTOOLS v2.2 By XeyyzuV2**
