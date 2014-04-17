cobbler_enhance
===============

How to install
--------------
  * You should install Cobbler 2.4.0, then mv /usr/share/cobbler/web/cobbler_web /usr/share/cobbler/web/cobbler_web.bak<br />
  * Checkout cobbler_enhance to /usr/share/cobbler/web/cobbler_web<br />
  * Copy cobbler_web/tools/jviewer to /usr/local/bin/ and chmod +x /usr/local/bin/jviewer<br />
  # 待测Copy cobbler_web/static/style.css to /var/www/cobbler_webui_content/style.css<br />
  # 待测Copy cobbler_web/static/cobbler.js to /var/www/cobbler_webui_content/cobbler.js<br />
  * mkdir /var/www/html/Java then chmod 777 /var/www/html/Java<br />
  * change ip: templates/console_page.tmpl and templates/generic_list.tmpl, replace 172.18.10.1 with your cobbler ipaddress <br />
  * service httpd restart<br />

What's new we added
-------------------
  * Console connect<br />
  * Power on/off of host<br />
  * Bios reboot<br />
  * Pxe reboot<br />
  * Rebuild Host<br />
  * Rebuild All Selected Host<br />
  * Clear the left tab<br />

Server Supported
-------------------
  * Supermicro<br />
  * TYAN<br />

Demo Screen
-----------
![github](http://raw.github.com/niuzhenguo/cobbler_enhance/master/screenshot/system.png)

![github](http://raw.github.com/niuzhenguo/cobbler_enhance/master/screenshot/console_redirection.png)

![github](http://raw.github.com/niuzhenguo/cobbler_enhance/master/screenshot/console.png)
