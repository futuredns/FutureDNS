# FutureDNS

Future DNS is a privacy friendly DNS service that blocks ads, trackers and malware. All servers support DNSSEC, DNS-over-TLS, DNS-over-HTTPS and DNS-over-QUIC, and do not log any data.


# DNS Servers

## Encrypted DNS 

### Anycast Network
              
DNS over HTTPS `https://dns.futuredns.me/dns-query/`

DNS over TLS `tls://dns.futuredns.me`

DNS over QUIC `quic://dns.futuredns.me`


## Unencrypted DNS 


### Europe

| Location       | Address                             |               
|----------------|-------------------------------------|
| London, UK        | `52.56.224.201`|
| Milan, Italy      | `15.161.11.3`|
| Stockholm, Sweden | `13.49.168.178`|


### North America

| Location       | Address                             |               
|----------------|-------------------------------------|
| Ashburn, USA      | `52.0.69.145`|
| San Francisco, USA | `13.56.204.161`|
| Montreal, Canada | `3.97.137.100`|

### Asia

| Location       | Address                             |               
|----------------|-------------------------------------|
| Singapore      | `54.254.82.60`|
| Tokyo, Japan   | `54.199.94.55`|
| Mumbai, India  | `3.7.162.217`|

### South America

| Location       | Address                             |               
|----------------|-------------------------------------|
| São Paulo, Brazil      | `177.71.191.153`|

## Privacy & Security

The servers use AdGuard Home, and are hosted on AWS. AWS do not have acess to any data processed in our servers, and all our servers are encrypted.
We do not register any logs and the client's IP adresses are anonymized. EDNS is disabled by default.

## New Servers

New servers will be added soon. If you want, you can request a server creating a issue in this repository or sending an e-mail to contact@futuredns.me

## Privacy & Security

The servers use AdGuard Home, and are hosted on AWS. AWS do not have acess to any data processed in our servers, and all our servers are encrypted.
We do not register any logs and the client's IP adresses are anonymized. EDNS is disabled by default.

## Service Status

To check service status, go to https://status.futuredns.me.

## Blocklists and Allowlists

### Blocklists

AdGuard DNS filter - https://adguardteam.github.io/AdGuardSDNSFilter/Filters/filter.txt

OISD Blocklist Basic - https://abp.oisd.nl/basic/

Perflyst and Dandelion Sprout's Smart-TV Blocklist - https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/SmartTV-AGH.txt

Dandelion Sprout's Anti-Malware List - https://raw.githubusercontent.com/DandelionSprout/adfilt/master/Alternate%20versions%20Anti-Malware%20List/AntiMalwareAdGuardHome.txt

WindowsSpyBlocker - https://raw.githubusercontent.com/crazy-max/WindowsSpyBlocker/master/data/hosts/spy.txt

Dandelion Sprout's Extremely Condensed Lists - https://raw.githubusercontent.com/DandelionSprout/adfilt/master/ExtremelyCondensedList.txt

1Hosts (Lite) - https://o0.pages.dev/Lite/adblock.txt

GoodByeAds - https://raw.githubusercontent.com/jerryn70/GoodbyeAds/master/Hosts/GoodbyeAds.txt

### Allowlists

Falukorv List - https://raw.githubusercontent.com/DandelionSprout/adfilt/master/FalukorvList.txt

anudeepND whitelist - https://raw.githubusercontent.com/anudeepND/whitelist/master/domains/whitelist.txt

Spotify Whitelist - https://gist.githubusercontent.com/captainhook/9eb4132d6e58888e37c6bc6c73dd4e60/raw/d5a9ee1f720a431ddc8021540181b53f9864760f/SpotifyWhitelist

## Contact
If you have any questions about the service, as well as suggestions, feel free to contact us at contact@futuredns.me

## Special thanks

 AdGuard Home - https://github.com/AdguardTeam/AdguardHome
 
 Unbound - https://www.nlnetlabs.nl/projects/unbound/about/
 
 AWS Activate - https://aws.amazon.com/activate/
 
 Through of AWS Activate for startups program, which gave us credits to develop our project, we were able to deploy this infrastructure.


