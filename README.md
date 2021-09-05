# Daraz-logout-CSRF
If a user makes a request to "https://member.daraz.lk/user/logout" the user is logged out. This action can be forced by another website by loading the URL in an image tag etc... or if the user is tricked into clicking opening the URL.

This when chained with other vulnerabilities could be serious issue and stop users from being able to use the politeia system.

Further reading:
https://www.owasp.org/index.php/Cross-Site_Request_Forgery_(CSRF)
https://www.owasp.org/index.php/Cross-Site_Request_Forgery_(CSRF)_Prevention_Cheat_Sheet
https://hackerone.com/reports/223329
https://labs.detectify.com/2017/03/15/loginlogout-csrf-time-to-reconsider/
http://www.tothenew.com/blog/understanding-the-csrfcross-site-request-forgery-vulnerability/
