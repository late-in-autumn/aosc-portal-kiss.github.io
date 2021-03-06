---
layout: post
title: 'AOSA-2016-0033: Update Apache HTTPD'
type: news
important: true
---

Please update your `httpd` package to version `2.4.23-1`.

A 0-day vulnerability was recently announced by Apache, "Server memory can be exhausted and service denied when HTTP/2 is used". And a CVE was consequently assigned for this vulnerability:

[CVE-2016-8740](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2016-8740).

Relevant documentation:

- [Original GitHub issue, containing mailing list post](https://github.com/AOSC-Dev/aosc-os-abbs/issues/518)