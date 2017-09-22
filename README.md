phois
=====

A \*nix WHOIS wrapper written in Python with automatic TLD lookup.

**Disclaimer:** Despite the name, this project has no relation to [Pho][1], any of it's great qualities, or what it "is"

## Dependencies
### Python modules:
* requests
* argparse
* re
* os

### \*nix binaries:
* whois

## Intent
* To allow for automatic TLD lookups in less common domain names. GNU jwhois only has pre-configured default WHOIS servers for common TLDs

## Install
```
git clone https://github.com/nckrse/phois.git
cd phois
pip install .
```

## Usage
Simply run a query against a given domain
```
phois example.bingo
```

## Contributing
If thou shalt possess a feel for the act of contribution, then thou shalt feel free to forketh and submit pull requests!

[1]: https://en.wikipedia.org/wiki/Pho
