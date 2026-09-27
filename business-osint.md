# business osint

## Finding Acquisitions

* You’ve profiled one entity under one name.
* But targets run many brands, and parents absorb the companies they acquire.
* Acquisitions = new apex domains = fresh, often forgotten attack surface.
* Here: use corporate-OSINT to find a target’s acquisitions & subsidiaries, then pivot them into live domains. Example — Tesla.

SEC EDGAR is the free database of US public-company filings. In every annual 10-K, Exhibit 21.1 — “Subsidiaries of the Registrant” — lists the company’s legal entities and their jurisdictions. This is the most authoritative list of entity names for reverse-WHOIS and registry pivots. Search the company (or CIK), open the newest 10-K, open the EX-21.1 exhibit.
