# reference-files

Yes, these are my IP addresses. Yes, they are public. No, I don't want to hear about it.

## What Is This?

A collection of reference files used across various infrastructure services — firewall allow-lists, device group lists, site-to-site VPN endpoints, and other network reference data.

## Why Is This Public?

Because sometimes the most pragmatic solution to "how do I get a firewall rule to consistently reference the right IPs" is "put them somewhere every system can reach." That somewhere is here. On the internet. In a public GitHub repo. You're reading it right now.

Security through obscurity was never the plan. The security *is* the firewall.

## Isn't That a Security Risk?

Knowing my IP addresses tells you approximately as much as knowing my street address tells you about whether you can walk into my house. The answer in both cases is: no, not really, the locks are the security — not the secret location.

If you're genuinely worried about this, I appreciate your concern. The firewalls do not.

## Contents

| File | Description |
|---|---|
| `firewall-lists/Allowed2_Internet_IPs.txt` | IPs permitted outbound to the internet. Yes, those are mine. |
| `firewall-lists/Allowed2_Internet_Servers.txt` | Servers permitted outbound to the internet. Still mine. |
| `firewall-lists/WanEdge-S2S.txt` | Site-to-site VPN edge endpoints. Public IPs. On the internet. In a repo. Yep. |
| `firewall-lists/Device-DomainControllers.txt` | Domain controller reference list. |
| `firewall-lists/Device-Resolvers.txt` | DNS resolver reference list. |
| `firewall-lists/VMware-ESX-Hosts.txt` | ESX host reference list. |
| `firewall-lists/VMware-ESX-Management.txt` | ESX management interface reference list. |
| `firewall-lists/RFC6890.txt` | Special-purpose IP ranges per RFC 6890. These ones aren't mine — they belong to the IETF. |
