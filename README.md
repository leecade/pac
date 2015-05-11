# pac

PAC file from GFWList.

@TODO

## nginx

```
server {
    listen  80;
    default_type application/x-ns-proxy-autoconfig;
    root /path/to/pac;
    index proxy.pac;
}
```

> ref
https://github.com/breakwa11/gfw_whitelist