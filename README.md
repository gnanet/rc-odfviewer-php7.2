# rc-odfviewer-php7.2
This is an OpenDocument viewer plugin for Roundcube based upon the original v1.0 code (not Kolab).  This fixes a couple of error messages with PHP 7.2:

<ul>PHP Deprecated:  mktime(): You should be using the time() function instead in /var/www/roundcube/plugins/odfviewer/odfviewer.php on line 144</ul>
<ul>PHP Warning:  Use of undefined constant RCMAIL_CHARSET - assumed 'RCMAIL_CHARSET' (this will throw an Error in a future version of PHP) in /var/www/roundcube/plugins/odfviewer/odfviewer.php on line 101</ul>
  
<b>Installation</b>
---
Extract these files into a plugin directory called "odfviewer".<br>
Make sure the "files" directory is writeable to the web server.<br>
Add the plugin to your Roundcube "/config/config.inc.php" file.

<b>Support</b>
---
Offered "As Is" without support of any kind.
