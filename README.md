# Sephia Mail

A blistering fast, secure, virus free, and PGP cryptography based alternative to GMail. Reclaim your 
privacy **TODAY**!

![alt tag](media/screenshot.png)

See a video about Sephia [here](https://www.youtube.com/watch?v=_hRZnQCCKyY), 
or [here]() for a deeper introduction to Sephia.

## Installation

First download [Phosphorus Five](https://github.com/polterguy/phosphorusfive). Then follow the recipe below

* Put the main _"/sephia-mail/"_ folder inside of your _"/phosphorusfive/core/p5.webapp/system42/apps/"_ 
* Create a MySQL database, and create a connection string in your web.config, and name it "sephia"
* Install GnuPG and create a keypair matching your email address

Restart your web server process, and enjoy.

Hint, you'll need to have either Xamarin, MonoDevelop or Visual Studio installed locally to test it on your
development machine, in addition to access to some MySQL instance, where you can create your database.

No teddy bears was harmed during the creation of this system!
