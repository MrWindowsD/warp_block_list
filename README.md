# warp_block_list
A personal list of domains that block WARP for configuration in Sing-box or other traffic filtering apps

# custom-rules
Here is a list of DNS rules for exceptions at the “package_name” level: [“ru.sberbankmobile”] -> ‘outbound’: “direct”
For example:
``` json
{
  "tag": "my-custom-rules",
  "type": "remote",
  "format": "source",
  "url": "https://raw.githubusercontent.com/Daniil/my-rules/main/custom-rules.json",
  "download_detour": "auto-test" 
}
```
