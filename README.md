# Daraz-logout-CSRF
If a user makes a request to "https://member.daraz.lk/user/logout" the user is logged out. This action can be forced by another website by loading the URL in an image tag etc... or if the user is tricked into clicking opening the URL.
<br>
This when chained with other vulnerabilities could be serious issue and stop users from being able to use the politeia system.
<br><br>
Further reading:<br>
https://www.owasp.org/index.php/Cross-Site_Request_Forgery_(CSRF)<br>
https://www.owasp.org/index.php/Cross-Site_Request_Forgery_(CSRF)_Prevention_Cheat_Sheet<br>
https://hackerone.com/reports/223329<br>
https://labs.detectify.com/2017/03/15/loginlogout-csrf-time-to-reconsider/<br>
http://www.tothenew.com/blog/understanding-the-csrfcross-site-request-forgery-vulnerability/<br>
