# NS_ERROR_NET_INADEQUATE_SECURITY
Source : ( https://anandthearchitect.com/2018/10/22/firefox-error-code-ns_error_net_inadequate_security/ )

### If you get this error (NS_ERROR_NET_INADEQUATE_SECURITY) when visting HTTPS site on Firefox, 
that means the web server has something wrong with SSL certificate (old ciphers, lower TLS version).

Here is how to fix your Firefox to access that page:

    Open Firefox and type about:config in the address bar
    Click on I accept the risk button
    Type http2 in search box
    Find network.http.spdy.enabled.http2 and double click to make it false (to disable http2).
![image](https://anandthearchitect.files.wordpress.com/2018/10/screen-shot-2018-10-21-at-10-08-40-pm.png)
That’s all. You may need to close Firefox and reopen it.
