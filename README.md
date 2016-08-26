# Plexidex
Export Plex Media Server Movie library to HTML/PHP

## Change History
### v0.0.1
This is the initial upload to gage the interest of other Plex users.

This package will require a webserver running php, and a network connection to your Plex Media Server

Upload contents to a PHP webserver and set the permissions of the temp directory to 0744. Set the permissions of settings.inc to 0600. All other files should be 0644.

Edit the settings.inc file to add your Plex IP address or hostname, port number, and X-Plex-Token.

Then open your browser and go to <webserverpath>/index.php?refresh

This should prompt you to choose your desired movie index sections. Check the desired sections and click save.

With your page still set to ?refresh, click the sort links on the left to refresh their sort orders.

Once that is done, you can access the page without ?refresh. To refresh your HTML in the future, just visit with ?refresh again.

Feedback is welcome!
