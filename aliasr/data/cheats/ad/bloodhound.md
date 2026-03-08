# bloodhound
#target/remote #os/linux #cat/ad

## bloodhound-ce
```
bloodhound-ce-python --zip -c All -d <domain> -dc <dc_fqdn> -ns <ip> -u '<user>' <auth>
```

## bloodhound.py
```
bloodhound.py --zip -c All -d <domain> -dc <dc_fqdn> -ns <ip> -u '<user>' <auth>
```

## Upload Bloodhound Data
```
BHCEupload -dir <bh_zip> -tokenid $BH_TOKEN_ID -tokenkey $BH_TOKEN_KEY -url http://127.0.0.1:<bh_port|8080>
```
