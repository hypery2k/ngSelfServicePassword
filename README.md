# ngSelfServicePassword

ngSelfServicePassword is a PHP application that allows users to change their password in an LDAP directory. It's based on [Self Service Password](http://ltb-project.org/wiki/documentation/self-service-password) and aims to provide an Bootstrap-Angular-Based Frontend.

The application can be used on standard LDAPv3 directories (OpenLDAP, OpenDS, ApacheDS, Sun Oracle DSEE, Novell, etc.) and also on Active Directory.

It has the following features:

* Samba mode to change Samba passwords
* Active directory mode
* Local password policy:
  * Minimum/maximum length
  * Forbidden characters
  * Upper, Lower, Digit or Special characters counters
  * Reuse old password check
  * Complexity (different class of characters)
* Help messages
* Reset by questions
* Reset by mail challenge (token sent by mail)
* Reset by SMS (trough external Email 2 SMS service)
* reCAPTCHA (Google API)
* Mail notification after password change
