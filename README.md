*NOT MANTAINED*

##Zolid AJAX Chat 0.1.0
This is an PHP + jQuery driven AJAX live chat or Shoutbox if you will. It comes with a profanity filter which can be switched on and off, XSS protection thanks for the HTML Purifier, chat rooms and more. This is a fairly easy to use, modify and integrate into any current website or login system. The visuals is made with the Twitter Bootstrap.

##Install
* Upload the files to your webhost.
* Import the .sql file to your database
* Edit the "livechat.processor.php" file with the SQL connection information.

##Admin Installation
1. Open the file "request.php"<br>
2. From the line 11 to the line 14 you have to insert your database informations.


Using a login system for "admin.php" and "request.php" is hightly suggested because these files are the ones that handles the database requests. If you do not know how to create a login system you can find one here: http://www.php-login.net/

The minimal version with some changes is enough to keep your database secure.

##Contact
If you have feature requests, suggestions or other feel free to contact me on Twitter:

https://twitter.com/stetto98

##Thanks
* [Twitter Bootstrap](https://github.com/twitter/bootstrap)
* [HTML Purifier](http://htmlpurifier.org/)

##License
Released under the MIT License - http://opensource.org/licenses/mit-license.php
