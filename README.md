# Sephia Mail

A blistering fast, secure, virus free, and PGP cryptography based alternative to GMail. Reclaim your 
privacy **TODAY**!

![alt tag](media/screenshot.png)

See an introductory video about Sephia [here](https://www.youtube.com/watch?v=_hRZnQCCKyY), 
or [here](https://www.youtube.com/watch?v=lzRJGU2UrT0) for a deeper introduction to Sephia, demonstrating it in practice.

## Installation

First download [Phosphorus Five](https://github.com/polterguy/phosphorusfive). Then follow the recipe below

* Put the main _"/sephia-mail/"_ folder inside of your _"/phosphorusfive/core/p5.webapp/system42/apps/"_ folder
* Create a MySQL database, and create a connection string in your web.config, and name it "sephia"
* Install GnuPG, and create a keypair matching your email address

Restart your web server process, configure Sephia, and enjoy.

Hint, you'll need to have either Xamarin, MonoDevelop, or Visual Studio installed locally, to test it on your
development machine - In addition to access to a MySQL instance, where you can create your database.

**Disclaimer;** _"No teddy bears was harmed during the creation of Sephia Mail!"_
