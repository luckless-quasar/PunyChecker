# PunyChecker
## Description
My modest attempt to make an extension that "Checks if the current domain uses Punycode".

## Background
The first documentation of the problem was demonstrated in 2017 :
- https://www.xudongz.com/blog/2017/idn-phishing/
See also :
- https://en.wikipedia.org/wiki/Punycode
- https://en.wikipedia.org/wiki/Website_spoofing

Sadly, the problem still occurs nowadays and is actively exploited :
- https://www.bleepingcomputer.com/news/security/fake-keepass-site-uses-google-ads-and-punycode-to-push-malware/

## Other mitigation
Issue is solved on Chromium and derivated since years (Chrome 59).
On Firefox, another possible mitigation is to enable the "network.IDN_show_punycode" parameter available at `about:config`.
See : https://kb.mozillazine.org/Network.IDN_show_punycode
