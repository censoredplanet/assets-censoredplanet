# assets-censoredplanet
This repository contains frequently updated asset files for Censored Planet data analysis.

[**blockpage_signature.json**](https://assets.censoredplanet.org/blockpage_signatures.json)
This file contains frequently observed patterns in blockpages, with appropriate labels for each pattern. 
Signatures must be matched in this order - Commercial products (prod), national firewalls (nat), ISP filters (isp), corporation (corp), unknown (unk), general (gen).
All the signatures except the ones in gen should be unique to the label. 
All patterns are in PCRE format. 

[**false_positive_signatures.json**](https://assets.censoredplanet.org/false_positive_signatures.json)
This file contains frequently observed unexpected responses which do not indicate censorship. These patterns should be matched before blockpage patterns. 
All patterns are in PCRE format.