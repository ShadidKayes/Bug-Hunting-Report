==================================================
1. AUTHENTICATION, AUTHORIZATION & SESSION MANAGEMENT
==================================================

[ Broken Authentication & Session Issues ]
- https://hackerone.com/reports/284 | Broken Authentication and session management OWASP A2
- https://hackerone.com/reports/288 | Session Management
- https://hackerone.com/reports/353 | Session not expired on logout
- https://hackerone.com/reports/737 | Improper session management
- https://hackerone.com/reports/2421 | Value of JSESSIONID and XSRF token parameter in cookie remains same before and after login
- https://hackerone.com/reports/2559 | Broken Authentication (including Slack OAuth bugs)
- https://hackerone.com/reports/7041 | iOS application does not destroy session upon logout
- https://hackerone.com/reports/15785 | Session not invalidated after password reset
- https://hackerone.com/reports/15852 | Non Validation of session after password reset
- https://hackerone.com/reports/17383 | Category- Broken Authentication and Session Management (leads to account compromise)
- https://hackerone.com/reports/17474 | Broken Authentication and Session Management
- https://hackerone.com/reports/55530 | Authentication Failed Mobile version

[ Account Takeover & Identity Impersonation ]
- https://hackerone.com/reports/280 | Real impersonation
- https://hackerone.com/reports/477 | Flawed account creation process allows registration of usernames corresponding to existing file names
- https://hackerone.com/reports/546 | Logical issues with account settings
- https://hackerone.com/reports/727 | Switching the user to the attacker's account
- https://hackerone.com/reports/774 | Log in a user to another account
- https://hackerone.com/reports/6907 | Session Token is not Verified while changing Account Setting's which Result In account Takeover
- https://hackerone.com/reports/6910 | Full account takeover using CSRF and password reset
- https://hackerone.com/reports/25281 | Change Any username and profile link in hackerone
- https://hackerone.com/reports/46618 | Frictionless Transferring of Wallet Ownership

[ Password Reset & Recovery Flaws ]
- https://hackerone.com/reports/738 | Information disclosure (reset password token) and changing the user's password
- https://hackerone.com/reports/742 | A password reset page does not properly validate the authenticity token at the server side
- https://hackerone.com/reports/809 | Improperly implemented password recovery link functionality
- https://hackerone.com/reports/6884 | Leaking Referrer in Reset Password Link
- https://hackerone.com/reports/8082 | Password Reset Bug
- https://hackerone.com/reports/15166 | Password reset token not expiring
- https://hackerone.com/reports/18698 | Resubmitted with POC #18685 Password reset CSRF
- https://hackerone.com/reports/23363 | Forgot Password Issue
- https://hackerone.com/reports/38343 | Issue with password change
- https://hackerone.com/reports/42587 | Vimeo.com Insecure Direct Object References Reset Password

[ Multi-Factor Authentication (MFA/2FA) ]
- https://hackerone.com/reports/7369 | 2 factor authentication design flaw
- https://hackerone.com/reports/10554 | Bypassing 2FA for BTC transfers
- https://hackerone.com/reports/50884 | Bypass pin (4 digit passcode on your android app)


==================================================
2. OAUTH & THIRD-PARTY INTEGRATION VULNERABILITIES
==================================================
- https://hackerone.com/reports/2228 | Login CSRF using Twitter OAuth
- https://hackerone.com/reports/2575 | Slack OAuth2 "redirect_uri" Bypass
- https://hackerone.com/reports/3596 | OAuth access_token stealing in Phabricator
- https://hackerone.com/reports/3930 | OAuth Stealing Attack (New)
- https://hackerone.com/reports/5314 | Coinbase Android Application - Bitcoin Wallet Leaks OAuth Response Code
- https://hackerone.com/reports/6017 | Facebook Takeover using Slack using 302 from files.slack.com with access_token
- https://hackerone.com/reports/31168 | Cryptographic Side Channel in OAuth Library
- https://hackerone.com/reports/44492 | Flaw in login with twitter to steal Oauth tokens
- https://hackerone.com/reports/46485 | Problem with OAuth
- https://hackerone.com/reports/55140 | Race Conditions in OAuth 2 API implementations
- https://hackerone.com/reports/55525 | Open redirection in OAuth


==================================================
3. CROSS-SITE SCRIPTING (XSS)
==================================================

[ Reflected XSS ]
- https://hackerone.com/reports/2497 | Reflective XSS can be triggered in IE
- https://hackerone.com/reports/2777 | Reflected Xss
- https://hackerone.com/reports/9318 | Home page reflected XSS
- https://hackerone.com/reports/17540 | Reflected XSS in Pastebin-view
- https://hackerone.com/reports/42582 | Vimeo.com - Reflected XSS Vulnerability
- https://hackerone.com/reports/42584 | Vimeo.com - reflected xss vulnerability
- https://hackerone.com/reports/43672 | player.vimeo.com - Reflected XSS Vulnerability
- https://hackerone.com/reports/44798 | Vimeo Search - XSS Vulnerability
- https://hackerone.com/reports/50134 | XSS in original referrer after follow
- https://hackerone.com/reports/53098 | XSS in twitter.com/safety/unsafe_link_warning

[ Stored XSS ]
- https://hackerone.com/reports/2617 | Stored XSS in www.slack-files.com
- https://hackerone.com/reports/2625 | Stored XSS in username.slack.com
- https://hackerone.com/reports/2652 | Stored XSS in Channel Chat
- https://hackerone.com/reports/4114 | Persistent XSS: Editor link
- https://hackerone.com/reports/4561 | Stored XSS in Slackbot Direct Messages
- https://hackerone.com/reports/6002 | Stored XSS in Slack.com
- https://hackerone.com/reports/7121 | Persistent Cross Site Scripting within the IRCCloud Pastebin
- https://hackerone.com/reports/7441 | Dangerous Persistent xss
- https://hackerone.com/reports/9375 | Stored XSS in all fields in Basic Google Maps Placemarks Settings
- https://hackerone.com/reports/9774 | Stored XSS Found
- https://hackerone.com/reports/10297 | Stored XSS in slack.com (integrations)
- https://hackerone.com/reports/11919 | Stored XSS on http://top.mail.ru
- https://hackerone.com/reports/11927 | Stored XSS on http://cards.mail.ru
- https://hackerone.com/reports/27846 | Stored xss
- https://hackerone.com/reports/33018 | a stored xss in slack integration
- https://hackerone.com/reports/36986 | [Stored XSS] vine.co - profile page
- https://hackerone.com/reports/41758 | Stored XSS in api key of operator wallet
- https://hackerone.com/reports/42161 | stored xss in transaction
- https://hackerone.com/reports/54719 | e.mail.ru stored XSS in agent via sticker (smile)
- https://hackerone.com/reports/55842 | [persistent cross-site scripting] customers can target admins

[ General XSS / Context-Specific XSS ]
- https://hackerone.com/reports/2439 | Cross Site Scripting (XSS) - app.relateiq.com
- https://hackerone.com/reports/9391 | Xss in CampTix Event Ticketing
- https://hackerone.com/reports/11073 | XSS in gist integration
- https://hackerone.com/reports/11410 | XSS in https://e.mail.ru/cgi-bin/lstatic (Limited use)
- https://hackerone.com/reports/12588 | XSS in a file or folder name
- https://hackerone.com/reports/13195 | auth.mail.ru: XSS in login form
- https://hackerone.com/reports/18691 | XSS in editor by any user
- https://hackerone.com/reports/20049 | Cross-site Scripting in mailing (username)
- https://hackerone.com/reports/20720 | cloud.mail.ru: File upload XSS using Content-Type header
- https://hackerone.com/reports/21150 | Flash XSS on swfupload.swf showing at app.mavenlink.com
- https://hackerone.com/reports/26935 | XSS via .eml file
- https://hackerone.com/reports/27511 | ads.twitter.com xss
- https://hackerone.com/reports/28150 | Cross site scripting on ads.twitter.com
- https://hackerone.com/reports/28832 | touch.mail.ru XSS via message id
- https://hackerone.com/reports/29328 | XSS platform.twitter.com
- https://hackerone.com/reports/29360 | XSS platform.twitter.com | video-js metadata
- https://hackerone.com/reports/32519 | XSS in fabric.io
- https://hackerone.com/reports/33091 | DOM Cross-Site Scripting ( XSS )
- https://hackerone.com/reports/34725 | XSS via Fabrico Account Name
- https://hackerone.com/reports/35363 | [static.qiwi.com] XSS proxy.html
- https://hackerone.com/reports/35413 | [send.qiwi.ru] XSS at auth?login=
- https://hackerone.com/reports/36319 | [qiwi.com] /oauth/confirm.action XSS
- https://hackerone.com/reports/38189 | xss in /browse/contacts/
- https://hackerone.com/reports/38345 | [sms.qiwi.ru] XSS via Request-URI
- https://hackerone.com/reports/38615 | [connect.mail.ru] Memory Disclosure / IE XSS
- https://hackerone.com/reports/41856 | HTML/XSS rendered in Android App of Crashlytics through fabric.io
- https://hackerone.com/reports/42393 | XSS on partners.uber.com
- https://hackerone.com/reports/42702 | APIs for channels allow HTML entities that may cause XSS issue
- https://hackerone.com/reports/44217 | Application XSS filter function Bypass may allow Multiple stored XSS
- https://hackerone.com/reports/44512 | XSS on any site that includes the moogaloop flash player
- https://hackerone.com/reports/45484 | XSS on Vimeo
- https://hackerone.com/reports/47536 | [ishop.qiwi.com] XSS + Misconfiguration
- https://hackerone.com/reports/52822 | XSS with Time-of-Day Format
- https://hackerone.com/reports/54321 | Xss in website's link
- https://hackerone.com/reports/54327 | Persistent cross-site scripting (XSS) in map attribution


==================================================
4. CROSS-SITE REQUEST FORGERY (CSRF)
==================================================
- https://hackerone.com/reports/547 | CSRF login
- https://hackerone.com/reports/2427 | XSRF token problem
- https://hackerone.com/reports/2628 | CSRF vulnerability on https://sehacure.slack.com/account/settings
- https://hackerone.com/reports/5946 | Marking notifications as read CSRF bug
- https://hackerone.com/reports/6871 | Login CSRF
- https://hackerone.com/reports/6872 | Sign up CSRF
- https://hackerone.com/reports/7531 | Login CSRF can be bypassed
- https://hackerone.com/reports/10563 | CSRF on "Set as primary" option on the accounts page
- https://hackerone.com/reports/10829 | CSRF in function "Set as primary" on accounts page
- https://hackerone.com/reports/15412 | Leaking CSRF token over HTTP resulting in CSRF protection bypass
- https://hackerone.com/reports/21069 | Login CSRF
- https://hackerone.com/reports/26647 | CSRF protection bypass on any Django powered site via Google Analytics
- https://hackerone.com/reports/44146 | Make API calls on behalf of another user (CSRF protection bypass)
- https://hackerone.com/reports/47472 | CSP Bypass: Click handler for links with data-method="post" can cause authenticity_token to be sent off domain
- https://hackerone.com/reports/49935 | rails-ujs will send CSRF tokens to other origins
- https://hackerone.com/reports/49974 | The csrf token remains same after user logs in
- https://hackerone.com/reports/52635 | UniFi v3.2.10 Cross-Site Request Forgeries / Referer-Check Bypass
- https://hackerone.com/reports/55911 | CSRF token fixation in facebook store app


==================================================
5. SQL INJECTION (SQLi)
==================================================
- https://hackerone.com/reports/9919 | SQL injection [дырка в движке форума]
- https://hackerone.com/reports/9921 | Time based sql injection
- https://hackerone.com/reports/10037 | SQL inj
- https://hackerone.com/reports/10081 | SQL
- https://hackerone.com/reports/10468 | SQL inj
- https://hackerone.com/reports/11861 | SQL injection update.mail.ru
- https://hackerone.com/reports/15762 | SQL Injection on 11x11.mail.ru
- https://hackerone.com/reports/28449 | Active Record SQL Injection Vulnerability Affecting PostgreSQL
- https://hackerone.com/reports/28450 | Active Record SQL Injection Vulnerability Affecting PostgreSQL
- https://hackerone.com/reports/31756 | Drupal 7 pre auth sql injection and remote code execution


==================================================
6. IDOR & BROKEN ACCESS CONTROL
==================================================
- https://hackerone.com/reports/3356 | UnAuthorized Editorial Publishing to Blogs
- https://hackerone.com/reports/13959 | privilege escalation
- https://hackerone.com/reports/16315 | Abusing VCS control on phabricator
- https://hackerone.com/reports/21210 | privilege escalation
- https://hackerone.com/reports/27404 | Delete Credit Cards from any Twitter Account in ads.twitter.com
- https://hackerone.com/reports/31082 | Unauthorized Tweeting on behalf of Account Owners
- https://hackerone.com/reports/35287 | getting emails of users/removing them from victims account
- https://hackerone.com/reports/38965 | Phabricator Diffusion application allows unauthorized users to delete mirrors
- https://hackerone.com/reports/42961 | fabric.io - app member can make himself an admin
- https://hackerone.com/reports/43065 | Fabric.io - an app admin can delete team members from other user apps
- https://hackerone.com/reports/43617 | Adding profile picture to anyone on Vimeo
- https://hackerone.com/reports/43770 | Ability to Download Music Tracks Without Paying
- https://hackerone.com/reports/45960 | Insecure Direct Object Reference - Unauthorized access to Videos of Private Channel
- https://hackerone.com/reports/46113 | Can message users without the proper authorization
- https://hackerone.com/reports/46397 | Insecure Direct Object Reference vulnerability
- https://hackerone.com/reports/46429 | Team member invitations to sandboxed teams are not invalidated consistently
- https://hackerone.com/reports/46747 | Team admin can change unauthorized team setting
- https://hackerone.com/reports/46750 | Team admin can change unauthorized team setting
- https://hackerone.com/reports/47888 | Reporting user's profile by using another people's ID
- https://hackerone.com/reports/47940 | Team admin can add billing contacts
- https://hackerone.com/reports/48422 | Team member invitations to sandboxed teams are not invalidated consistently (v2)
- https://hackerone.com/reports/50776 | A user can edit comments even after video comments are disabled
- https://hackerone.com/reports/50786 | A user can add videos to other user's private groups
- https://hackerone.com/reports/50829 | A user can post comments on other user's private videos
- https://hackerone.com/reports/51817 | Post in private groups after getting removed
- https://hackerone.com/reports/52176 | Insecure Direct Object References in https://vimeo.com/forums
- https://hackerone.com/reports/52181 | Insecure Direct Object References that allows to read any comment
- https://hackerone.com/reports/52646 | Insecure direct object reference - have access to deleted DM's
- https://hackerone.com/reports/52707 | Invite any user to your group without even following him
- https://hackerone.com/reports/52708 | Share your channel to any user on vimeo without following him
- https://hackerone.com/reports/52982 | Add or Delete the videos in watch later list of any user
- https://hackerone.com/reports/53858 | Insecure Direct Object Reference - access to other user/group DM's
- https://hackerone.com/reports/54610 | Logout any user of same team
- https://hackerone.com/reports/55670 | Fabric.io: Ex-admin of an organization can delete team members


==================================================
7. SSRF & XXE VULNERABILITIES
==================================================
- https://hackerone.com/reports/713 | Upload profile photo from URL
- https://hackerone.com/reports/12583 | XXE and SSRF on webmaster.mail.ru
- https://hackerone.com/reports/14033 | connect.mail.ru: SSRF
- https://hackerone.com/reports/14127 | SSRF on https://whitehataudit.slack.com/account/photo
- https://hackerone.com/reports/16571 | SSRF (Portscan) via Register Function (Custom Server)
- https://hackerone.com/reports/36450 | [send.qiwi.ru] Soap-based XXE vulnerability /soapserver/
- https://hackerone.com/reports/53088 | SSRF vulnerability (access to metadata server on EC2 and OpenStack)
- https://hackerone.com/reports/55431 | XML Parser Bug: XXE over which leads to RCE


==================================================
8. OPEN REDIRECT & HEADER INJECTION / CRLF
==================================================

[ Open Redirect ]
- https://hackerone.com/reports/2622 | URL redirection flaw
- https://hackerone.com/reports/7357 | Host Header is not validated resulting in Open Redirect
- https://hackerone.com/reports/16718 | Open Redirect login account
- https://hackerone.com/reports/25160 | Open redirection on secure.phabricator.com
- https://hackerone.com/reports/26962 | open redirect in rfc6749
- https://hackerone.com/reports/28865 | Redirect FILTER bypass in report/comment
- https://hackerone.com/reports/38157 | [qiwi.com] Open Redirect
- https://hackerone.com/reports/39631 | Open redirection in fabric.io
- https://hackerone.com/reports/48516 | Redirect URL in /intent/ functionality is not properly escaped
- https://hackerone.com/reports/49759 | Open Redirect leak of authenticity_token lead to full account take over
- https://hackerone.com/reports/50752 | open redirect sends authenticity_token to any website or (ip address)
- https://hackerone.com/reports/52035 | Open redirect in "Language change"
- https://hackerone.com/reports/55546 | Open Redirect after login at http://ecommerce.shopify.com

[ CRLF / Host Header / HTTP Response Splitting ]
- https://hackerone.com/reports/13286 | Host Header Injection - irccloud.com
- https://hackerone.com/reports/36105 | CRLF Injection [ishop.qiwi.com]
- https://hackerone.com/reports/39181 | [vimeopro.com] CRLF Injection
- https://hackerone.com/reports/52042 | HTTP Response Splitting (CRLF injection) in report_story
- https://hackerone.com/reports/53843 | HTTP Response Splitting (CRLF injection) due to headers overflow


==================================================
9. SUBDOMAIN TAKEOVER & DNS ISSUES
==================================================
- https://hackerone.com/reports/487 | DNS Cache Poisoning
- https://hackerone.com/reports/1509 | DNS Misconfiguration
- https://hackerone.com/reports/6353 | Wildcard DNS in website
- https://hackerone.com/reports/32825 | URGENT - Subdomain Takeover on media.vine.co due to unclaimed domain pointing to AWS
- https://hackerone.com/reports/38007 | Subdomain Takeover using blog.greenhouse.io pointing to Hubspot
- https://hackerone.com/reports/42236 | URGENT - Subdomain Takeover on users.tweetdeck.com
- https://hackerone.com/reports/49663 | URGENT - Subdomain Takeover on status.vimeo.com due to unclaimed domain pointing to statuspage.io


==================================================
10. MEMORY CORRUPTION, HEAP/BUFFER OVERFLOWS & RCE
==================================================
- https://hackerone.com/reports/499 | Ruby: Heap Overflow in Floating Point Parsing
- https://hackerone.com/reports/500 | OpenSSH: Memory corruption in AES-GCM support
- https://hackerone.com/reports/523 | PHP openssl_x509_parse() Memory Corruption Vulnerability
- https://hackerone.com/reports/1356 | PHP Heap Overflow Vulnerability in imagecrop()
- https://hackerone.com/reports/2106 | Flash type confusion vulnerability leads to code execution
- https://hackerone.com/reports/2170 | Flash double free vulnerability leads to code execution
- https://hackerone.com/reports/4689 | SPDY memory corruption
- https://hackerone.com/reports/4690 | SPDY heap buffer overflow
- https://hackerone.com/reports/6389 | Integer overflow in strop.expandtabs
- https://hackerone.com/reports/12297 | Python vulnerability: reading arbitrary process memory
- https://hackerone.com/reports/12497 | Adobe Flash Player FileReference Use-after-Free Vulnerability
- https://hackerone.com/reports/16392 | Abusing daemon logs for Privilege escalation under certain scenarios
- https://hackerone.com/reports/17688 | LZ4 Core
- https://hackerone.com/reports/18843 | use-after-free vulnerability in Flash Player
- https://hackerone.com/reports/20671 | integer overflow in 'buffer' type allows reading memory
- https://hackerone.com/reports/28445 | SPL ArrayObject/SPLObjectStorage Unserialization Type Confusion Vulnerabilities
- https://hackerone.com/reports/30567 | Adobe Flash Player MP4 Use-After-Free Vulnerability
- https://hackerone.com/reports/31408 | Adobe Flash Player Out-of-Bound Read/Write Vulnerability
- https://hackerone.com/reports/35102 | Locale::parseLocale Double Free
- https://hackerone.com/reports/36264 | mod_proxy_fcgi buffer overflow
- https://hackerone.com/reports/36279 | Adobe Flash Player MP4 Use-After-Free Vulnerability
- https://hackerone.com/reports/37240 | Race condition in Flash workers may cause an exploitable double free
- https://hackerone.com/reports/38170 | Misc Python bugs (Memory Corruption & Use After Free)
- https://hackerone.com/reports/43443 | PyUnicode_FromFormatV crasher
- https://hackerone.com/reports/44513 | RCE due to Web Console IP Whitelist bypass in Rails 4.0 and 4.1
- https://hackerone.com/reports/47012 | Adobe Flash Player Out-of-Bound Access Vulnerability
- https://hackerone.com/reports/47227 | Race condition in workers may cause an exploitable double free by abusing bytearray.compress()
- https://hackerone.com/reports/47232 | Use after free during the StageVideoAvailabilityEvent can result in arbitrary code execution
- https://hackerone.com/reports/47234 | Use After Free in Flash MessageChannel.send can cause arbitrary code execution
- https://hackerone.com/reports/47779 | Heap overflow in H. Spencer's regex library on 32 bit systems
- https://hackerone.com/reports/48100 | Bad Write in TTF font parsing (win32k.sys)
- https://hackerone.com/reports/49408 | RCE через JDWP
- https://hackerone.com/reports/55017 | Multiple Python integer overflows
- https://hackerone.com/reports/55018 | Segmentation fault for invalid PSS parameters
- https://hackerone.com/reports/55028 | Free called on unitialized pointer in exif.c
- https://hackerone.com/reports/55029 | Use after free vulnerability in unserialize() with DateTimeZone
- https://hackerone.com/reports/55030 | SoapClient's __call() type confusion through unserialize()
- https://hackerone.com/reports/55033 | Use after free vulnerability in unserialize()


==================================================
11. DENIAL OF SERVICE (DoS)
==================================================
- https://hackerone.com/reports/390 | Pixel flood attack
- https://hackerone.com/reports/400 | GIF flooding
- https://hackerone.com/reports/454 | PNG compression DoS
- https://hackerone.com/reports/5928 | Uncontrolled Resource Consumption with XMPP-Layer Compression
- https://hackerone.com/reports/13748 | Potential denial of service in hackerone.com/teams/new
- https://hackerone.com/reports/17785 | Denial of Service
- https://hackerone.com/reports/20861 | moderate: mod_deflate denial of service
- https://hackerone.com/reports/42797 | Denial of Service in Action Pack Exception Handling
- https://hackerone.com/reports/55716 | Force 500 Internal Server Error on any shop (for one user)


==================================================
12. TLS / SSL & CRYPTOGRAPHIC ISSUES
==================================================
- https://hackerone.com/reports/501 | TLS Virtual Host Confusion
- https://hackerone.com/reports/6626 | TLS heartbeat read overrun (Heartbleed)
- https://hackerone.com/reports/7277 | TLS Triple Handshake Attack
- https://hackerone.com/reports/16568 | Failed Certificate Validation On Custom Server (Register)
- https://hackerone.com/reports/30852 | Relateiq SSLv3 deprecated protocol vulnerability
- https://hackerone.com/reports/31415 | PoodleBleed
- https://hackerone.com/reports/32570 | OpenSSL HeartBleed (CVE-2014-0160)
- https://hackerone.com/reports/41240 | POODLE Bug: 199.16.156.44, 199.16.156.108, mx4.twitter.com
- https://hackerone.com/reports/44294 | Heartbleed: my.com (185.30.178.33) port 1433
- https://hackerone.com/reports/49139 | scfbp.tng.mail.ru: Heartbleed
- https://hackerone.com/reports/50170 | FREAK: Factoring RSA_EXPORT Keys to Impersonate TLS Servers
- https://hackerone.com/reports/50885 | CVE-2014-0224 openssl ccs vulnerability


==================================================
13. FLASH & BROWSER SANDBOX BYPASSES
==================================================
- https://hackerone.com/reports/2107 | Handling of jar: URIs bypasses AllowScriptAccess=never
- https://hackerone.com/reports/2140 | Flash local-with-fileaccess Sandbox Bypass
- https://hackerone.com/reports/27651 | Flash Local Sandbox Bypass
- https://hackerone.com/reports/3455 | flash content type sniff vulnerability in api.slack.com
- https://hackerone.com/reports/6380 | Same Origin Security Bypass Vulnerability
- https://hackerone.com/reports/10373 | Bypassing Same Origin Policy With JSONP APIs and Flash
- https://hackerone.com/reports/15362 | Flash Sandbox Bypass
- https://hackerone.com/reports/42240 | chrome allows POST requests with custom headers using flash + 307 redirect
- https://hackerone.com/reports/47495 | Same Origin Policy bypass
- https://hackerone.com/reports/51265 | Flash Cross Domain Policy Bypass by Using File Upload and Redirection - only in Chrome
- https://hackerone.com/reports/54094 | HTTP MitM on Flash Player settings manager allows attacker to set sandbox settings


==================================================
14. INFORMATION DISCLOSURE & DATA LEAKAGE
==================================================
- https://hackerone.com/reports/2221 | CSS leaks SCSS debug info
- https://hackerone.com/reports/2584 | Weird Bug - Ability to see partial of other user's notification
- https://hackerone.com/reports/4409 | TRACE disclosure attack may be possible
- https://hackerone.com/reports/26825 | Full path disclosure at ads.twitter.com
- https://hackerone.com/reports/29835 | Profile Pic padding (Length-hiding) fails due to use of GZIP
- https://hackerone.com/reports/31383 | Ability to see common response titles of other teams (limited)
- https://hackerone.com/reports/33935 | File Name Enumeration
- https://hackerone.com/reports/39486 | No bruteforce protection leads to enumeration of emails in http://e.mail.ru/
- https://hackerone.com/reports/41469 | Error stack trace
- https://hackerone.com/reports/43440 | Arbitrary file existence disclosure in Action Pack
- https://hackerone.com/reports/43988 | twitter android app Fragment Injection
- https://hackerone.com/reports/43998 | CRITICAL full source code/config disclosure for Cameo
- https://hackerone.com/reports/44052 | Hadoop Node available to public
- https://hackerone.com/reports/44727 | Insecure Data Storage in Vine Android App
- https://hackerone.com/reports/46345 | Directory index and information disclosure
- https://hackerone.com/reports/46366 | Error stack trace
- https://hackerone.com/reports/47627 | Email Enumeration (POC)
- https://hackerone.com/reports/49035 | HDFS NameNode Public disclosure
- https://hackerone.com/reports/49170 | Information disclosure - emails disclosed in response > staging.seatme.us
- https://hackerone.com/reports/49806 | Twitter Ads Campaign information disclosure through admin without any authentication


==================================================
15. EMAIL & DOMAIN SECURITY
==================================================
- https://hackerone.com/reports/120 | Missing SPF for hackerone.com
- https://hackerone.com/reports/575 | Email spoofing
- https://hackerone.com/reports/2224 | Bypass auth.email-domains
- https://hackerone.com/reports/2233 | Bypass auth.email-domains (2)
- https://hackerone.com/reports/16935 | e.mail.ru: SMS spam with custom content
- https://hackerone.com/reports/18992 | Possibility to attach any mobile number to any email
- https://hackerone.com/reports/23852 | money.mail.ru: Странное поведение SMS
- https://hackerone.com/reports/29331 | No email verification on username change
- https://hackerone.com/reports/30975 | Improper Verification of email address while saving Account Settings
- https://hackerone.com/reports/34112 | SMPT Protection not used, I can hijack your email server.
- https://hackerone.com/reports/54779 | Missing spf flags for myshopify.com


==================================================
16. BUSINESS LOGIC, INPUT VALIDATION & OTHER FLAWS
==================================================

[ Business Logic & Rate Limiting ]
- https://hackerone.com/reports/3441 | Captcha Bypass With Extension
- https://hackerone.com/reports/5933 | Multiple Issues related to registering applications
- https://hackerone.com/reports/6350 | creating titleless and non-closable bugs
- https://hackerone.com/reports/6883 | Bruteforcing irccloud login
- https://hackerone.com/reports/14570 | Login password guessing attack
- https://hackerone.com/reports/27166 | Missing Rate Limiting on https://twitter.com/account/complete
- https://hackerone.com/reports/29234 | Credit Card Validation Issue
- https://hackerone.com/reports/30238 | New Device confirmation tokens are not properly validated.
- https://hackerone.com/reports/35237 | Gain reputation by creating a duplicate of an existing report
- https://hackerone.com/reports/36211 | Logic Issue with Reputation: Boost Reputation Points
- https://hackerone.com/reports/36594 | New Device Confirmation, token is valid until not used.
- https://hackerone.com/reports/38232 | Breaking Bugs as team member
- https://hackerone.com/reports/43602 | Buying ondemand videos that 0.1 and sometimes for free
- https://hackerone.com/reports/43850 | abusing Thumbnails to see a private video
- https://hackerone.com/reports/44888 | Improper way of validating a program
- https://hackerone.com/reports/45368 | ftp upload of video allows naming that is not sanitized
- https://hackerone.com/reports/49561 | Vimeo + & Vimeo PRO Unautorised Tax bypass
- https://hackerone.com/reports/50941 | A user can enhance their videos with paid tracks without buying the track
- https://hackerone.com/reports/54641 | Captcha Bypass in Snapchat's Geofilter Submission Process

[ Input Validation & Miscellaneous ]
- https://hackerone.com/reports/298 | RTL override symbol not stripped from file names
- https://hackerone.com/reports/3227 | Control Characters Not Stripped From Username on Signup
- https://hackerone.com/reports/3370 | Directory traversal attack in view resolver
- https://hackerone.com/reports/3921 | Control character allowed in username
- https://hackerone.com/reports/20391 | m.agent.mail.ru: Подделываем j2me app-descriptor
- https://hackerone.com/reports/20616 | e.mail.ru: File upload "Chapito" circus
- https://hackerone.com/reports/21034 | Invoice Details activate JS that filled in
- https://hackerone.com/reports/21248 | Content spoofing at Stripe Integrations
- https://hackerone.com/reports/22093 | Content Spoofing all Integrations in https://team.slack.com/services/new/
- https://hackerone.com/reports/23386 | Redirect while opening links in new tabs
- https://hackerone.com/reports/27987 | Window Opener Property Bug
- https://hackerone.com/reports/28500 | iOS App can establish Facetime calls without user's permission
- https://hackerone.com/reports/29480 | Unvalidated Channel names causes IRC Command Injection
- https://hackerone.com/reports/29491 | homograph attack. IDNs displayed in unicode in bug reports
- https://hackerone.com/reports/29839 | GNU Bourne-Again Shell (Bash) 'Shellshock' Vulnerability
- https://hackerone.com/reports/31554 | Singup Page HTML Injection Vulnerability
- https://hackerone.com/reports/34084 | Bad extended ascii handling in HTTP 301 redirects of t.co
- https://hackerone.com/reports/34686 | Ошибка фильтрации
- https://hackerone.com/reports/39428 | Phabricator Phame Blog Skins Local File Inclusion
- https://hackerone.com/reports/46072 | Vulnerability with the way \ escaped characters in links are rendered
- https://hackerone.com/reports/46818 | Twitter Card - Parent Window Redirection
- https://hackerone.com/reports/46916 | Markdown parsing issue enables insertion of malicious tags and event handlers
- https://hackerone.com/reports/47280 | JSON keys are not properly escaped
- https://hackerone.com/reports/48065 | open authentication bug
- https://hackerone.com/reports/49652 | Improperly validated fields allows injection of arbitrary HTML via spoofed React objects
- https://hackerone.com/reports/54631 | Vulnerable to JavaScript injection. (WXS)


==================================================
17. UI SECURITY & CLIENT-SIDE FLAWS
==================================================
- https://hackerone.com/reports/8724 | Clickjacking
- https://hackerone.com/reports/8846 | localStorage не чистится после выхода
- https://hackerone.com/reports/14631 | Clickjacking at https://www.mavenlink.com/ main website
- https://hackerone.com/reports/21110 | Clickjacking
- https://hackerone.com/reports/2735 | HTML injection in "Invite Collaborators"
- https://hackerone.com/reports/321 | CSP not consistently applied
- https://hackerone.com/reports/6935 | Missing X-Content-Type-Options
- https://hackerone.com/reports/9479 | Anti-MIME-Sniffing header X-Content-Type-Options header has not been set
- https://hackerone.com/reports/17160 | Password Policy issue (Weak Protect)
- https://hackerone.com/reports/3986 | Securing sensitive pages from SearchBots
- https://hackerone.com/reports/5786 | Coinbase Android Security Vulnerabilities
- https://hackerone.com/reports/6877 | Unsecure cookies, cookie flag secure not set
- https://hackerone.com/reports/7036 | Bug in iOS application which could lead to unauthorised access
- https://hackerone.com/reports/7931 | Issue with remember_user_token
- https://hackerone.com/reports/842 | Autocomplete enabled in Paypal preferences
- https://hackerone.com/reports/16330 | Multiple issues in looking-glass software (aka from web to BGP injections)
- https://hackerone.com/reports/20873 | rsync hash collisions may allow an attacker to corrupt or modify files
- https://hackerone.com/reports/4638 | Duplicate of #4550
- https://hackerone.com/reports/54733 | Sandboxed iframes don't show confirmation screen
- https://hackerone.com/reports/55028 | Free called on unitialized pointer in exif.c



