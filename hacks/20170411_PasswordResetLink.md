
Editing:
- https://wiki.pumpingstationone.org/MediaWiki:Userlogin-helplink2
Setting it to:
Reset your password
- https://wiki.pumpingstationone.org/MediaWiki:Helplogin-url
Setting it to:
https://members.pumpingstationone.org/accounts/password_reset/

And setting in the config file of mediawiki (localsettings.php.j2):

$wgPasswordResetRoutes = false;

That removed the previous reset link password.

