# website osint

{% embed url="https://youtu.be/v4kGkd6wQt0?si=GiB3DoCAHZQwtE_u" %}

### All-in-one tool

{% embed url="https://osint.sh/" %}
down
{% endembed %}

### Digital Certs

We can use these to reverse search a certificate to find related websites/ Subdomains

{% embed url="https://crt.sh/" %}

{% embed url="https://ui.ctsearch.entrust.com/ui/ctsearchui" %}

{% embed url="https://www.ssllabs.com/ssltest/" %}

#### Local Certificates downloading and analysing tools

{% embed url="https://github.com/g0ldencybersec/CloudRecon" %}

{% embed url="https://kaeferjaeger.gay/?dir=sni-ip-ranges" %}
Certs at cloud IPs downloaded weekly
{% endembed %}

### Internet Search Engines

Gives information about websites without scanning

{% embed url="https://search.censys.io/" %}

{% embed url="https://www.shodan.io/" %}

#### Shodan Based Tools

{% embed url="https://github.com/s0md3v/Smap" %}
<p align="center"><strong>passive Nmap like scanner built with shodan.io</strong></p>
{% endembed %}

{% embed url="https://github.com/Dheerajmadhukar/karma_v2" %}
Uses Inbuilt Shodan querries to find information about a domain
{% endembed %}

### Finding Web Technology

{% embed url="https://www.wappalyzer.com/" %}

{% embed url="https://builtwith.com/" %}

{% embed url="https://osint.sh/stack/" %}

{% embed url="https://whatcms.org/" %}

{% embed url="https://www.kali.org/tools/whatweb/" %}

### Finding Load Balancer

{% embed url="https://www.kali.org/tools/lbd/" %}

### WHOIS /ASN Information Checker

{% embed url="https://whois.domaintools.com/" %}

{% embed url="https://who.is/" %}

{% embed url="https://www.whois.com/whois/" %}

{% embed url="https://www.kali.org/tools/whois/" %}

#### Reverse Whois

{% embed url="https://viewdns.info/reversewhois/" %}

{% embed url="https://whoisfreaks.com/tools/user/whois/reverse/search" %}

{% embed url="https://www.reversewhois.io/" %}

{% embed url="https://osint.sh/reversewhois/" %}

#### Historical Whois

{% embed url="https://whoisfreaks.com/tools/user/whois/history/lookup" %}

{% embed url="https://www.whoxy.com/whois-history/" %}

{% embed url="https://research.domaintools.com/research/whois-history/" %}

{% embed url="https://whois-history.whoisxmlapi.com/" %}

#### Find Similar domain with keyword to check whois

{% embed url="https://osint.sh/domain/" %}

{% embed url="https://instantdomainsearch.com/" %}

{% embed url="https://dnschecker.org/search-domain-name-checker.php>?" %}

{% embed url="https://search.dnslytics.com/" %}

### Security Headers

{% embed url="https://securityheaders.com/" %}

#### Curl

```bash
curl -I https://certifiedhacker.com/
```

<figure><img src=".gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

{% embed url="https://www.grc.com/id/idserve.htm" %}

{% embed url="https://www.computec.ch/projekte/httprecon/" %}

#### **Browser Developer Tools**

You can check the Network tab to view the headers

### Find ASN Numbers

{% embed url="https://bgp.he.net/" %}
Can be helpful to locate more Websites
{% endembed %}

#### Find IP ranges of ASN

{% embed url="https://github.com/projectdiscovery/asnmap" %}

{% embed url="https://whois.arin.net/ui/query.do" %}

#### IP Addresses Information

{% embed url="https://ipinfo.io/AS18053" %}

{% embed url="https://github.com/owasp-amass/amass" %}

### Website Information Aggregators

All in one tools for Website OSINT

{% embed url="https://web-check.as93.net/" %}

{% embed url="https://centralops.net/co/domaindossier" %}

{% embed url="https://sitereport.netcraft.com/" %}

{% embed url="https://viewdns.info/" %}

#### Kali Tools

{% embed url="https://www.kali.org/tools/spiderfoot/" %}
