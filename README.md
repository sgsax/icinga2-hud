icinga2-hud
==========

Simple heads-up-display summary for Icinga2

This is a fork of my [icinga-hud](https://github.com/sgsax/icinga-hud) project, modified for use with Icinga2 and its new REST API.

The project includes a slightly modified bootstrap bundle (based on v. 3.2.0). My intent was to be able to post results on a large display (TV, 1920x1080), so I added some larger resolutions to the base bootstrap css. If you prefer another bootstrap bundle, perhaps your own, I have provided a patch file which you may use against your own copy.

Installation is simple: extract to a web server of your choosing and deploy a functioning site for it. Edit `config.php` with appropriate values for url, port, cgi path, username, and password. Hopefully, it is self-explanatory enough for most people who will use this application. Your host will also need an appropriate package to provide the PHP CURL and JSON libraries. Please check with your distro or platform documentation for details on how to do this.

Please see the [wiki](https://github.com/sgsax/icinga-hud/wiki) for screenshots.

Future plans include:
 * adding custom filter building on all pages
 * editing config info from within the application
 * making column count a configurable option (currently hard-coded for six columns)

Please use, fork, comment, and submit patches in good health!
