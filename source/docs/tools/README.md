# Introduction

## What?

Enumerating rools useful for discovering and exploiting API vulnerabilities.

## Why?

Three tools are especially useful for API hacking: [Chrome with DevTools](https://developer.chrome.com/docs/devtools/) 
or [FireFox Developer edition](https://www.mozilla.org/en-GB/firefox/developer/), [BurpSuite Pro](https://portswigger.net/burp), and [Postman](https://portswigger.net/bappstore/6ae9ede3630949748842a43518e840a7). 
There is a trial version of Burp Suite Pro, and not everyone can afford that. Several tools can replace what is missing in the free community edition.

## How?

* For capturing and modifying requests with Burp (rerouting web browser traffic to Burp before it
is sent to the API provider), set up FoxyProxy extension in Chrome (Socks5, 127.0.0.1, port 8080).
* Using FoxyProxy, select that proxy, go to http://burpsuite, and click CA Certificate to download the Burp Suite 
certificate. Save it and import it in the browser.
  * Firefox: open Preferences and use the search bar to look up certificates, and import the certificate 
  * Chrome: open Settings, use the search bar to look up certificates, select More -> Manage Certificates -> 
Authorities, and import the certificate 
* Make sure you havre git, python3, golang
* [Kiterunner](https://github.com/assetnote/kiterunner/releases)
* [Nikto](https://www.kali.org/tools/nikto/)
* [OWASP ZAP](https://owasp.org/www-project-zap/)
* [Wfuzz](https://github.com/xmendez/wfuzz)
* [Arjun](https://github.com/s0md3v/Arjun)
* [OWASP Amass](https://owasp-amass.com/)
