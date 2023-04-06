## CURL (POSIX)
curl 'https://desktop-release.notion-static.com/Notion%20Setup%202.0.41.exe' \
-H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/111.0' \
-H 'Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,*/*;q=0.8' \
-H 'Accept-Language: en-US,en;q=0.5' \
-H 'Accept-Encoding: gzip, deflate, br' \
-H 'Referer: https://www.notion.so/' \
-H 'DNT: 1'\
-H 'Connection: keep-alive' \
-H 'Upgrade-Insecure-Requests: 1' \
-H 'Sec-Fetch-Dest: document' \
-H 'Sec-Fetch-Mode: navigate' \
-H 'Sec-Fetch-Site: cross-site' \
-H 'Sec-Fetch-User: ?1' \
-H 'Pragma: no-cache' \
-H 'Cache-Control: no-cache' \
-H 'TE: trailers'

## CURL (Windows)
curl "https://desktop-release.notion-static.com/Notion^%^20Setup^%^202.0.41.exe" -H "User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/111.0" -H "Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,*/*;q=0.8" -H "Accept-Language: en-US,en;q=0.5" -H "Accept-Encoding: gzip, deflate, br" -H "Referer: https://www.notion.so/" -H "DNT: 1" -H "Connection: keep-alive" -H "Upgrade-Insecure-Requests: 1" -H "Sec-Fetch-Dest: document" -H "Sec-Fetch-Mode: navigate" -H "Sec-Fetch-Site: cross-site" -H "Sec-Fetch-User: ?1" -H "Pragma: no-cache" -H "Cache-Control: no-cache" -H "TE: trailers"

## Powershell
Invoke-WebRequest -UseBasicParsing -Uri "https://desktop-release.notion-static.com/Notion%20Setup%202.0.41.exe" `\
-UserAgent "Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/111.0" `\
-Headers @{ \
"Accept" = "text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,*/*;q=0.8" \
  "Accept-Language" = "en-US,en;q=0.5" \
  "Accept-Encoding" = "gzip, deflate, br" \
  "Referer" = "https://www.notion.so/" \
  "DNT" = "1" \
  "Upgrade-Insecure-Requests" = "1" \
  "Sec-Fetch-Dest" = "document" \
  "Sec-Fetch-Mode" = "navigate" \
  "Sec-Fetch-Site" = "cross-site" \
  "Sec-Fetch-User" = "?1" \
  "Pragma" = "no-cache" \
  "Cache-Control" = "no-cache" \
  "TE" = "trailers" \
} \
## Fetch
```
await fetch("https://desktop-release.notion-static.com/Notion%20Setup%202.0.41.exe", { 
    "credentials": "omit", 
    "headers": { 
        "User-Agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/111.0",   
        "Accept": "text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,*/*;q=0.8",   
        "Accept-Language": "en-US,en;q=0.5",   
        "Upgrade-Insecure-Requests": "1",   
        "Sec-Fetch-Dest": "document",   
        "Sec-Fetch-Mode": "navigate",   
        "Sec-Fetch-Site": "cross-site",   
        "Sec-Fetch-User": "?1",   
        "Pragma": "no-cache",   
        "Cache-Control": "no-cache"   
    },   
    "referrer": "https://www.notion.so/",   
    "method": "GET",   
    "mode": "cors"   
});   
```