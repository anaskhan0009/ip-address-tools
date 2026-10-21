# IP Address Tools — IPv4 Converter, Classifier & CIDR Calculator

A complete IPv4 toolbox in one page: convert any address between **dotted decimal, decimal integer, hexadecimal and binary**, instantly see whether it is **private, public, loopback, CGNAT, multicast or reserved**, and calculate full **CIDR ranges** — network, broadcast, first/last host and counts. Your conversions can be saved with labels in a local account.

**Live Demo:** https://anaskhan0009.github.io/ip-address-tools/

## Features

- **Local account system** — sign up / log in on this device (passwords stored only as salted SHA-256 hashes, never plain text), continue as guest, per-account data separation, account deletion, and Export / Import of your records as JSON
- **Full record manager (CRUD)** — create, view, edit and delete your own saved records; the core tool works fully without an account, signing in unlocks saving for saved conversions and lookups, each with its own label
- **Four-format converter** — paste dotted, decimal, 0x hex or 32-bit binary and get every representation plus a per-octet breakdown table
- **Address classification** — RFC 1918 private ranges, loopback, link-local/APIPA, CGNAT 100.64/10, multicast, benchmarking and the three documentation TEST-NETs, each explained in plain language
- **CIDR calculator** — network, broadcast, usable host range, total/usable counts, subnet mask and wildcard mask for any /0–/32

## How to Use

1. Type or paste an IP address in any format and press Convert.
2. Use the CIDR calculator with an IP and prefix length to map out a whole network block.
3. Press “Save this conversion”, then label and annotate it in your records below.
4. Export your records as JSON any time from Profile & settings.

## Why Address Classes Matter

Most “weird IP” mysteries are just address classes: a 169.254 address means DHCP failed, a 100.64 address means your ISP uses carrier-grade NAT (which is why port forwarding fails), and a 192.168 address can never be reached from the internet directly. Knowing which range an address belongs to turns guesswork into a 10-second diagnosis.

## Ethical Use

This is a **defensive, educational tool** — it only ever helps you understand and improve your own security and privacy. Nothing here can be used to attack, track or deceive anyone else.

## Tech

Single self-contained `index.html` — HTML, CSS, vanilla JavaScript, WebCrypto (salted SHA-256 password hashing), localStorage persistence. No servers, no tracking, no external requests.

---

Built by **Dinal Studios** — free cyber security tools and web apps.
GitHub: https://github.com/anaskhan0009
