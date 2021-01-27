# assets-censoredplanet
This repo contains frequently updated asset files for censored planet public analysis repo

**blockpage__signature.json**

Signatures must be matched in this order - Commercial products (prod), national firewalls (nat), ISP filters (isp), corporation (corp), unknown (unk), general (gen).
All the signatures except the ones in gen should be unique to the label. 

*To use the patterns for regular expression matching, pre-processing of the data might be needed for those that have semantic meaning for regular expression, e.g. adding quotes before open left parentheses.*
