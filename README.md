# open-neuro-wiki

[![Join the chat at https://gitter.im/open-neuroscience/wiki](https://badges.gitter.im/open-neuroscience/wiki.svg)](https://gitter.im/open-neuroscience/wiki?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Open Neuroscience wiki system


## implementing the wiki:
This all started from a conversation [here](https://github.com/auto-pi-lot/autopilot/discussions/192) and [here](https://gitter.im/open-neuroscience/wiki?utm_source=share-link&utm_medium=link&utm_campaign=share-link).

For Open Neuroscience, we got a domain and hosted server at Namecheap. The nice things about this hosting company are:
- their price
- can choose where the server will be located
- cPanel for control of the system is quite complete.
 - command line control
 - git installed by default
 - easy install for mediawiki, wordpress, forums, etc
 - unlimited subdomains
 - easy cron jobs access
 - setting up python apps with easy

Steps are:
1. get a domain name and server time
2. access cPanel and using softaculous suite install mediaWiki - (1-click install) 
3. install extensions, packages and skins listed [here](https://wiki.auto-pi-lot.com/index.php/Special:Version)
 - note: most of this is done in command line, so it might be a good idea to get a bit familiar with how to navigate folders and display folder content using the command line of GNU/Linux systems. Also the some text is edited also in command line. We used vim for text editing, but there are other options of course. 
 - note: certain packages require download of a compressed file and decompressing that file into a specific folder. For instance the 'Arrays' package requires download and decompression of the downloaded file in the `extensions`. This can be done like so:
   - create a folder for the compressed files (jsut so things are organised): `mkdir snapshots`
   - move into said folder: `cd snapshots`
   - in the case of 'Arrays', download the package: `wget https://extdist.wmflabs.org/dist/extensions/Arrays-REL1_38-6ac129a.tar.gz`
   - decompress that file into the `extensions` folder: `tar -xzf Arrays-REL1_38-6ac129a.tar.gz -C ../extensions`
   
