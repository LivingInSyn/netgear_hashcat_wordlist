# netgear_hashcat_wordlist
Wordlist and hashcat ruleset for cracking the default netgear WPA passphrase. Created because netgear routers use a default key in the format:

```
{adjective}{noun}{3 digits}
```

# usage
```shell
hashcat -m 2500 capture.hccapx netgear_wordlist.txt -r netgear_hashcat_rules 
```
