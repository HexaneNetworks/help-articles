#### What happens when I secure my website?
Securing your website makes your website appear as **Secure** to the left of the web address (Location of this may vary depending on browser). Secure websites ensures that information that a user sends or receives through the website is private.

To make things easier for you - Hexane provides you with an SSL certificate. All you have to do is follow the method below to setup a functioning redirect.

#### Method
1. Login to [cPanel](https://cpanel.hexaneweb.com) by doing one of the following: using the login information provided in the **Web Hosting Information** email or using the cPanel shortcut in the [Billing Area](https://billing.hexanenetworks.com/)
2. Once you are in cPanel search for **File Manager** in the search bar and click on the appropriate result.
3. In the top right of the **File Manager** click on the **Settings** button. 
4. Proceed to tick the **Show Hidden Files** option and click the **Save** button in the bottom right of the **Settings** box.
5. Navigate to the ``public_html`` directory.
6. Click on the file titled ``.htaccess`` and proceed to click the **Edit** button in the top navigation bar. If this file doesn't exist - create the file.
7. Once the editing preferences dialogue appears, click the **Edit** button in the bottom right.
8. Once you are editing the correct file, input the following, **replace your.domain with your websites domain name**:
```
RewriteCond %{REQUEST_URI} !^/[0-9]+\..+\.cpaneldcv$
RewriteCond %{REQUEST_URI} !^/\.well-known/pki-validation/[A-F0-9]{32}\.txt(?:\ Comodo\ DCV)?$
RewriteEngine On
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://your.domain/$1 [R=301,L]
```
9. Click on the **Save Changes** and then the **Close** button in the top right of the page.
10. Navigate back to [cPanel](https://cpanel.hexaneweb.com).
11. Once you are in cPanel search for **SSL/TLS Status** in the search bar and click on the appropriate result.
12. Click on the **AutoSSL** button and allow the process to finish.

#### Example .htaccess
![](https://raw.githubusercontent.com/HexaneNetworks/help-assets/master/assets/example-htaccess.png)