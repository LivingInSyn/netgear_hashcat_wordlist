# netgear_hashcat_wordlist
Wordlist and hashcat ruleset for cracking the default netgear WPA passphrase. Created because netgear routers use a default key in the format:

```
{adjective}{noun}{3 digits}
```

# usage
*Note*: Requires hashcat_utils
```shell
./combinator3.bin wordlists/adjectives.txt wordlists/nounds.txt wordlists/numbers.txt |  hashcat -m 2500 capture.hccapx 
```

# Thanks
Thanks to @mikerod_sd for helping source the adj-noun pairs
