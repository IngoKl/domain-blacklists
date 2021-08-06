# Domain Blacklists

These are some (primarily personal) domain blacklists. I primarly use them, in addition to other lists, on [Pi-hole](https://pi-hole.net/)s.

## Lists

* `simple-sketchy-crypto.slist` contains domains related to sketchy crypto sites.
* `simple-unsorted.slist` contains unsorted (not yet sorted) domains (e.g., ads).

## Combined List

The individual `.slist`s are being combined into `combined.list` using `combine.sh`. 
For this to work, each `.slist` needs to end in a newline.
