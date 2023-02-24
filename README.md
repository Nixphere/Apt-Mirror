# Nixphere apt mirror
This is an APT mirror for Debian 9 - 12 (`stretch`, `buster`, `bullseye` and `bookwoorm`) which is located in Frankfurt am Main in germany

## Processor architecture
- `amd64` (64 Bit) Debian 9-12
- `i368` (32 Bit) Debian 9-12
- `arm64` (ARM 64 Bit) Debian 9-12
- `armfh` (ARM 32 Bit) Debian 9-12
- `armel` (ARM 32 Bit) Debian 9-12 

(I myself do not know the exact difference between `armfh` and `armel` but I know that <a href="http://www.raspbian.org/">raspbian</a> mostly runs on armfh or arm64)
## URL
| IPv | Protocol | URL |
|--|--|--|
| IPv4 & IPv6 | http | `http://deb.nixphere.de/` |
| IPv4 & IPv6 | https | `https://deb.nixphere.de/` |
| IPv4 | http | `http://deb.v4.nixphere.de/` |
| IPv4 | https | `https://deb.v4.nixphere.de/` |
| IPv6 | http | `http://deb.v6.nixphere.de/` |
| IPv6 | https | `https://deb.v6.nixphere.de/` |

## sources.list
Your sources.list should look like this after editing (some versions don't use deb-src (then just disregard and edit the exestirenenden))<br>
<img src="https://github.com/Nixphere/APt-Mirror/raw/main/Screenshot%202023-02-24%20014427.png">

