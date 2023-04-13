# Awesome Web Security

### 🐶 Curated list of Web Security materials and resources. 
#### Needless to say, most of websites on-line are suffered from various type of bugs, which might eventually lead to vulnerabilities. Why would this happen so often? Many factors can be involved, including misconfiguration, shortage of engineers' security skills, and etc. Therefore, here is the curated list of Web Security materials and resources for learning the cutting edge penetrating techniques.

---

<p align="center"><b>🌈 Want to strengthen your penetration skills?</b><br>I would recommend to play some <a href="https://github.com/apsdehal/awesome-ctf" target="_blank">awesome-ctf</a>.</p>

---

Check out my [repos](https://github.com/Xcod3bughunt3r) 🐾 or say *hi* on my [Twitter](https://twitter.com/Xcod3bughunt3r).

## Contents

- [Forums](#forums)
- [Useful Resources](#useful-resources)
    - [XSS](#useful-resources-xss)
    - [SQL Injection](#useful-resources-sql-injection)
    - [XML](#useful-resources-xml)
    - [CSRF](#useful-resources-csrf)
    - [Rails](#useful-resources-rails)
    - [AngularJS](#useful-resources-angularjs)
    - [SSL/TLS](#userful-resources-ssl-tls)
- [Evasions](#evasions)
	- [CSP](#evasions-csp)
    - [WAF](#evasions-waf)
    - [JSMVC](#evasions-jsmvc)
- [Tricks](#tricks)
    - [Remote Code Execution](#tricks-rce)
    - [XSS](#tricks-xss)
    - [SQL Injection](#tricks-sql-injection)
    - [SSRF](#tricks-ssrf)
    - [Header Injection](#tricks-header-injection)
    - [URL](#tricks-url)
    - [Others](#tricks-others)
- [Browser Exploitation](#browser-exploitation)
- [PoCs](#pocs)
    - [JavaScript](#pocs-javascript)
- [Tools](#tools)
    - [Code Generating](#tools-code-generating)
    - [Disassembler](#tools-disassembler)
    - [Fuzzing](#tools-fuzzing)
    - [Penetrating](#tools-penetrating)
    - [Leaking](#tools-leaking)
    - [Detecting](#tools-detecting)
    - [Preventing](#tools-preventing)
- [Blogs](#blogs)
- [Twitter Users](#twitter-users)
- [Practices](#practices)
    - [AWS](#practices-aws)
    - [XSS](#practices-xss)
- [Community](#community)
- [Miscellaneous](#miscellaneous)

## Forums

* [Drops (backup)](https://drops.secquan.org/) - Drops was known as a famous knowledge base for hacking technology.
* [Paper from Seebug](http://paper.seebug.org/) - Knowledge base for hacking technology built by [Seebug](http://seebug.org/).
* [Freebuf](http://www.freebuf.com/) - Freebuf is the most popular forum in China for exchanging and sharing hacking technology.
* [安全脉搏](https://www.secpulse.com/) - Blog for Security things.

## Useful Resources

<a name="useful-resources-xss"></a>
### XSS

* [H5SC](https://github.com/cure53/H5SC) - HTML5 Security Cheatsheet - Collection of HTML5 related XSS attack vectors by [@cure53](https://github.com/cure53).
* [XSS.png](https://github.com/jackmasa/XSS.png) - XSS mind map by [@jackmasa](https://github.com/jackmasa).

<a name="useful-resources-sql-injection"></a>
### SQL Injection

* [HQL for pentesters](http://blog.h3xstream.com/2014/02/hql-for-pentesters.html) - Brief introduction to Hibernate Query Injection.

<a name="useful-resources-xml"></a>
### XML

* [XML实体攻击 - 从内网探测到命令执行步步惊心](http://www.freebuf.com/video/49961.html), written by 张天琪.

<a name="useful-resources-csrf"></a>
### CSRF

* [讓我們來談談 CSRF](http://blog.techbridge.cc/2017/02/25/csrf-introduction/), written by [TechBridge](http://blog.techbridge.cc/).

<a name="useful-resources-rails"></a>
### Rails

* [Rails 動態樣板路徑的風險](http://devco.re/blog/2015/07/24/the-vulnerability-of-dynamic-render-paths-in-rails/), written by [Shaolin](http://devco.re/blog/author/shaolin/).
* [Rails Security](http://php.ph/wydrops/drops/Rails%20Security%20(%E4%B8%8A).pdf), written by [@qazbnm456](https://github.com/qazbnm456).

<a name="useful-resources-angularjs"></a>
### AngularJS

* [XSS without HTML: Client-Side Template Injection with AngularJS](http://blog.portswigger.net/2016/01/xss-without-html-client-side-template.html), written by [Gareth Heyes](https://www.blogger.com/profile/10856178524811553475).

<a name="useful-resources-ssl-tls"></a>
### SSL/TLS

* [SSL & TLS Penetration Testing](https://www.aptive.co.uk/blog/tls-ssl-security-testing/), written by [APTIVE](https://www.aptive.co.uk/).

## Evasions

<a name="evasions-csp"></a>
### CSP

* [CSP: bypassing form-action with reflected XSS](https://labs.detectify.com/2016/04/04/csp-bypassing-form-action-with-reflected-xss/), written by [Detectify Labs](https://labs.detectify.com/).

<a name="evasions-waf"></a>
### WAF

* [浅谈json参数解析对waf绕过的影响](https://xianzhi.aliyun.com/forum/read/553.html), written by [doggy](https://xianzhi.aliyun.com/forum/u.php?uid=1723895737531437).
* [Airbnb – When Bypassing JSON Encoding, XSS Filter, WAF, CSP, and Auditor turns into Eight Vulnerabilities](https://buer.haus/2017/03/08/airbnb-when-bypassing-json-encoding-xss-filter-waf-csp-and-auditor-turns-into-eight-vulnerabilities/), written by [@Brett Buerhaus](https://twitter.com/bbuerhaus).

<a name="evasions-jsmvc"></a>
### JSMVC

* [JavaScript MVC and Templating Frameworks](http://www.slideshare.net/x00mario/jsmvcomfg-to-sternly-look-at-javascript-mvc-and-templating-frameworks), written by [Mario Heiderich](http://www.slideshare.net/x00mario).

## Tricks

<a name="tricks-rce"></a>
### Remote Code Execution

* [Exploiting Node.js deserialization bug for Remote Code Execution](https://opsecx.com/index.php/2017/02/08/exploiting-node-js-deserialization-bug-for-remote-code-execution/), written by [OpSecX](https://opsecx.com/index.php/author/ajinabraham/).
* [eval长度限制绕过 && PHP5.6新特性](https://www.leavesongs.com/PHP/bypass-eval-length-restrict.html), written by [PHITHON](https://www.leavesongs.com/).
* [PHP垃圾回收机制UAF漏洞分析](http://www.freebuf.com/vuls/122938.html), written by [ph1re](http://www.freebuf.com/author/ph1re).
* [DRUPAL 7.X SERVICES MODULE UNSERIALIZE() TO RCE](https://www.ambionics.io/blog/drupal-services-module-rce), written by [Ambionics Security](https://www.ambionics.io/).
* [How we exploited a remote code execution vulnerability in math.js](https://capacitorset.github.io/mathjs/), written by [@capacitorset](https://github.com/capacitorset).
* [GitHub Enterprise Remote Code Execution](http://exablue.de/blog/2017-03-15-github-enterprise-remote-code-execution.html), written by [@iblue](https://github.com/iblue).

<a name="tricks-xss"></a>
### XSS

* [ECMAScript 6 from an Attacker's Perspective - Breaking Frameworks, Sandboxes, and everything else](http://www.slideshare.net/x00mario/es6-en), written by [Mario Heiderich](http://www.slideshare.net/x00mario).
* [How I found a $5,000 Google Maps XSS (by fiddling with Protobuf)
](https://medium.com/@marin_m/how-i-found-a-5-000-google-maps-xss-by-fiddling-with-protobuf-963ee0d9caff#.u50nrzhas), written by [Marin Moulinier](https://medium.com/@marin_m).

<a name="tricks-sql-injection"></a>
### SQL Injection

* [屌智硬之mysql不用逗号注入](http://www.jinglingshu.org/?p=2220), written by [jinglingshu](http://www.jinglingshu.org/?p=2220).
* [见招拆招：绕过WAF继续SQL注入常用方法](http://www.freebuf.com/articles/web/36683.html), written by [mikey](http://www.freebuf.com/author/mikey).
* [MySQL Error Based SQL  Injection Using  EXP](https://www.exploit-db.com/docs/37953.pdf), written by [@osandamalith](https://twitter.com/osandamalith).
* [SQL injection in an UPDATE query - a bug bounty story!](http://zombiehelp54.blogspot.jp/2017/02/sql-injection-in-update-query-bug.html), written by [Zombiehelp54](http://zombiehelp54.blogspot.jp/).

<a name="tricks-ssrf"></a>
### SSRF

* [SSRF in https://imgur.com/vidgif/url](https://hackerone.com/reports/115748), written by [aesteral](https://hackerone.com/aesteral).

<a name="tricks-header-injection"></a>
### Header Injection

* [Java/Python FTP Injections Allow for Firewall Bypass](http://blog.blindspotsecurity.com/2017/02/advisory-javapython-ftp-injections.html), written by [Timothy Morgan](https://plus.google.com/105917618099766831589).

<a name="tricks-url"></a>
### URL

* [URL Hacking - 前端猥琐流](http://php.ph/wydrops/drops/URL%20Hacking%20-%20前端猥琐流.pdf), written by [0x_Jin](http://xssec.lofter.com/).
* [Phishing with Unicode Domains](https://www.xudongz.com/blog/2017/idn-phishing/), written by [Xudong Zheng](https://www.xudongz.com/).
* [Unicode Domains are bad and you should feel bad for supporting them](https://www.vgrsec.com/post20170219.html), written by [VRGSEC](https://www.vgrsec.com/).

<a name="tricks-others"></a>
### Others

* [Some Tricks From My Secret Group](https://www.leavesongs.com/SHARE/some-tricks-from-my-secret-group.html), written by [PHITHON](https://www.leavesongs.com/).

## Browser Exploitation

* [First Step to Browser Exploitation](http://mashirogod.dothome.co.kr/index.php/2017/01/07/first-step-to-browser-exploitation/), written by [Brian Pak](http://mashirogod.dothome.co.kr/).
* [JSON hijacking for the modern web](http://blog.portswigger.net/2016/11/json-hijacking-for-modern-web.html), written by [portswigger](https://portswigger.net/).
* [IE11 Information disclosure - local file detection](https://www.facebook.com/ExploitWareLabs/photos/a.361854183878462.84544.338832389513975/1378579648872572/?type=3&theater), written by James Lee.

## PoCs

<a name="pocs-javascript"></a>
### JavaScript

* [js-vuln-db](https://github.com/tunz/js-vuln-db) - Collection of JavaScript engine CVEs with PoCs by [@tunz](https://github.com/tunz).
* [awesome-cve-poc](https://github.com/qazbnm456/awesome-cve-poc) - Curated list of CVE PoCs by [@qazbnm456](https://github.com/qazbnm456).
* [Some-PoC-oR-ExP](https://github.com/coffeehb/Some-PoC-oR-ExP) - 各种漏洞poc、Exp的收集或编写 by [@coffeehb](https://github.com/coffeehb).

## Tools

<a name="tools-code-generating"></a>
### Code Generating

* [VWGen](https://github.com/qazbnm456/lulumi-browser) - Vulnerable Web applications Generator by [@qazbnm456](https://github.com/qazbnm456).

<a name="tools-disassembler"></a>
### Disassembler

* [plasma](https://github.com/plasma-disassembler/plasma) - Plasma is an interactive disassembler for x86/ARM/MIPS by [@plasma-disassembler](https://github.com/plasma-disassembler).
* [radare2](https://github.com/radare/radare2) - Unix-like reverse engineering framework and commandline tools by [@radare](https://github.com/radare).
* [Iaitō](https://github.com/hteso/iaito) - Qt and C++ GUI for radare2 reverse engineering framework by [@hteso](https://github.com/hteso).

<a name="tools-fuzzing"></a>
### Fuzzing

* [wfuzz](https://github.com/xmendez/wfuzz) - Web application bruteforcer by [@xmendez](https://github.com/xmendez).
* [charsetinspect](https://github.com/hack-all-the-things/charsetinspect) - Script that inspects multi-byte character sets looking for characters with specific user-defined properties by [@hack-all-the-things](https://github.com/hack-all-the-things).
* [IPObfuscator](https://github.com/OsandaMalith/IPObfuscator) - Simple too to convert the IP to a DWORD IP by [@OsandaMalith](https://github.com/OsandaMalith).
* [wpscan](https://github.com/wpscanteam/wpscan) - WPScan is a black box WordPress vulnerability scanner by [@wpscanteam](https://github.com/wpscanteam).
* [JoomlaScan](https://github.com/drego85/JoomlaScan) - Free software to find the components installed in Joomla CMS, built out of the ashes of Joomscan by [@drego85](https://github.com/drego85).

<a name="tools-penetrating"></a>
### Penetrating

* [Burp Suite](https://portswigger.net/burp/) - Burp Suite is an integrated platform for performing security testing of web applications by [portswigger](https://portswigger.net/).
* [mitmproxy](https://github.com/mitmproxy/mitmproxy) - Interactive TLS-capable intercepting HTTP proxy for penetration testers and software developers by [@mitmproxy](https://github.com/mitmproxy).

<a name="tools-leaking"></a>
### Leaking

* [HTTPLeaks](https://github.com/cure53/HTTPLeaks) - All possible ways, a website can leak HTTP requests by [@cure53](https://github.com/cure53).
* [dvcs-ripper](https://github.com/kost/dvcs-ripper) - Rip web accessible (distributed) version control systems: SVN/GIT/HG... by [@kost](https://github.com/kost).
* [DVCS-Pillage](https://github.com/evilpacket/DVCS-Pillage) - Pillage web accessible GIT, HG and BZR repositories by [@evilpacket](https://github.com/evilpacket).

<a name="tools-detecting"></a>
### Detecting

* [sqlchop](https://github.com/chaitin/sqlchop) - [DEPRECATED] Novel SQL injection detection engine built on top of SQL tokenizing and syntax analysis by [chaitin](http://chaitin.com).
* [retire.js](https://github.com/RetireJS/retire.js) - Scanner detecting the use of JavaScript libraries with known vulnerabilities by [@RetireJS](https://github.com/RetireJS).
* [malware-jail](https://github.com/HynekPetrak/malware-jail) - Sandbox for semi-automatic Javascript malware analysis, deobfuscation and payload extraction by [@HynekPetrak](https://github.com/HynekPetrak).

<a name="tools-preventing"></a>
### Preventing

* [js-xss](https://github.com/leizongmin/js-xss) - Sanitize untrusted HTML (to prevent XSS) with a configuration specified by a Whitelist by [@leizongmin](https://github.com/leizongmin).

<a name="tools-others"></a>
### Others

* [Dnslogger](https://wiki.skullsecurity.org/index.php?title=Dnslogger) - DNS Logger by [@iagox86](https://github.com/iagox86).

## Blogs

* [Orange](http://blog.orange.tw/) - Taiwan's talented web penetrator.
* [leavesongs](https://www.leavesongs.com/) - China's talented web penetrator.
* [Broken Browser](https://www.brokenbrowser.com/) - Fun with Browser Vulnerabilities.
* [Blog of Osanda](https://osandamalith.com/) - Security Researching and Reverse Engineering.
* [BRETT BUERHAUS](https://buer.haus/) - Vulnerability disclosures and rambles on application security.
* [n0tr00t](https://www.n0tr00t.com/) - ~# n0tr00t Security Team.

## Twitter Users

* [@filedescriptor](https://twitter.com/filedescriptor) - Active penetrator often tweets and writes useful articles
* [@cure53berlin](https://twitter.com/cure53berlin) - [Cure53](https://cure53.de/) is a German cybersecurity firm.
* [@XssPayloads](https://twitter.com/XssPayloads) - The wonderland of JavaScript unexpected usages, and more.

## Practices

<a name="practices-aws"></a>
### AWS

* [FLAWS](http://flaws.cloud/) - Amazon AWS CTF challenge, written by [@0xdabbad00](https://twitter.com/0xdabbad00).

<a name="practices-xss"></a>
### XSS

* [alert(1) to win](https://alf.nu/alert1) - Series of XSS challenges, written by [@steike](https://twitter.com/steike).
* [prompt(1) to win](http://prompt.ml/) - Complex 16-Level XSS Challenge held in summer 2014 (+4 Hidden Levels), written by [@cure53](https://github.com/cure53).

## Community

* [Reddit](https://www.reddit.com/r/websecurity/)
* [Stack Overflow](http://stackoverflow.com/questions/tagged/security)

## Miscellaneous

* [awesome-bug-bounty](https://github.com/djadmin/awesome-bug-bounty) - Comprehensive curated list of available Bug Bounty & Disclosure Programs and write-ups by [@djadmin](https://github.com/djadmin).
* [bug-bounty-reference](https://github.com/ngalongc/bug-bounty-reference) - List of bug bounty write-up that is categorized by the bug nature by [@ngalongc](https://github.com/ngalongc).
* [如何正確的取得使用者 IP ？](http://devco.re/blog/2014/06/19/client-ip-detection/), written by [Allen Own](http://devco.re/blog/author/allenown).
* [1000php](https://github.com/Xyntax/1000php) - 1000个PHP代码审计案例(2016.7以前乌云公开漏洞) by [@Xyntax](https://github.com/Xyntax).
* [Brute Forcing Your Facebook Email and Phone Number](http://pwndizzle.blogspot.jp/2014/02/brute-forcing-your-facebook-email-and.html), written by [PwnDizzle](http://pwndizzle.blogspot.jp/).
* [GITLEAKS](https://gitleaks.com/) - Search engine for exposed secrets on lots of places.
* [Pentest + Exploit dev Cheatsheet wallpaper](http://i.imgur.com/Mr9pvq9.jpg) - Penetration Testing and Exploit Dev CheatSheet.
* [Hunting for Web Shells](https://www.tenable.com/blog/hunting-for-web-shells), written by [Jacob Baines](https://www.tenable.com/profile/jacob-baines).
* [The Definitive Security Data Science and Machine Learning Guide](http://www.covert.io/the-definitive-security-datascience-and-machinelearning-guide/), written by JASON TROS.
* [EQGRP](https://github.com/x0rz/EQGRP) - Decrypted content of eqgrp-auction-file.tar.xz by[@x0rz](https://github.com/x0rz).

