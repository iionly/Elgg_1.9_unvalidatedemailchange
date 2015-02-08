Unvalidated Email Change plugin
Latest Version: 1.10.2
Released: 2015-02-08
Contact: iionly@gmx.de
License: GNU General Public License version 2
Copyright: (c) iionly


Requirements:

You need to have the bundled uservalidationbyemail plugin enabled and the unvalidatedemailchange plugin must be placed below it to be able to change the email addresses of unvalidated accounts. Optional is the IP Tracker plugin.



What this plugin does:

This plugin adds the option to change the email address of unvalidated user accounts to the Elgg core unvalidated user account administration page (menu option "Administer" - "Users" - "Unvalidated" in admin section). This option might be useful in case the email address provided when registering the account is invalid (for example only due to a typo) and therefore resending of the validation email to the orginal address is doomed to bounce. If you know the correct address for this user, you can change the email address and then resend the validation email to the new email address.

If you have also the IP Tracker plugin installed, you will also see the IP addresses these accounts have been registered from.



Credits:

* I had gotten used to have the email change function available with the simpleusermanagement plugin by Pjotr Savitski in Elgg 1.7 and earlier. The built-in unvalidated user administration page was a nice addition to Elgg core but I was missing the email change function. Porting the complete simpleusermanagement plugin to Elgg 1.8 would have added some redundant features, so I decided to only implement the email change option. Nonetheless, I want to thank Pjotr for the simpleusermanagement plugin that is the basis of this plugin.

* Thanks a lot also to DhrupDeScoop and Matt Beckett who helped me a lot to get the ajax-driven Lightbox popup correctly implemented.



Installation:

1. Copy the unvalidatedemailchange plugin folder into you mod folder,
2. Enable the unvalidatedemailchange plugin in the admin section of your site.


Changelog:

1.10.2:

- Based on version 1.9.2,
- Fix of deprecation issues occuring on Elgg 1.10 (namely changing output/confirmlink view to output/url view).

1.9.2:

- Updated version 1.8.2 for Elgg 1.9.

1.8.2:

- show IP addresses used when registering the unvalidated accounts.

1.9.1:

- Updated version 1.8.1 for Elgg 1.9.

1.8.1:

- French translation added (thank to emanwebdev),

1.8.0:

- Initial release.
