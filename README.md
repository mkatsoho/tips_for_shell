# tips_for_shell

bash tips, mainly in macos

## tar but exclude

```bash
# exclude should use '' for *, e.g. --exclude '*.json'
tar -zcvf little_app.tgz --exclude little_app/node_modules  --exclude little_app/.git  --exclude '*.json' little_app 
```

## timestamp

```bash
## convert timestamp to date string. Not suitable for macos.
date -d @1455086371603
Tue Nov 7 10:46:43 UTC 48079

## show datetime string
date '+%Y%m%dT%H%M%S'
20171011T161024
```
