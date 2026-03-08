# bloodhound
#target/remote #os/linux #cat/ad

## One-Liner Collect + Upload
```
bloodhound-ce-python -c All -u <user> <auth> -d <domain> -ns <ip> --zip && BHCEupload.py -dir $(ls -t *_bloodhound.zip | head -n1) -tokenid $BH_TOKEN_ID -tokenkey $BH_TOKEN_KEY -url http://127.0.0.1:8080
```

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
BHCEupload.py -dir <bh_zip> -tokenid $BH_TOKEN_ID -tokenkey $BH_TOKEN_KEY -url http://127.0.0.1:<bh_port|8080>
```
