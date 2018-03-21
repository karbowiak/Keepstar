# Keepstar
EVE Online SSO Auth For Discord

https://discord.gg/ZWmzTP3 To discuss and for support.

Intended to be used with https://github.com/shibdib/Firetail **BUT** can be safely used standalone.

*If you're a Dramiel or Opux user check the wiki for how to convert to Keepstar.*

What It Does
-
This program will host a web page that members of your discord server can visit to be assigned roles based off of
corporation, alliance, and player specific roles. It will then ensure the player remains in these roles and remove them 
if the players status changes (via a cron job).


Requirements
-
- PHP7 
- Webserver (Apache/NGINX/Whatever You're Comfortable With)
- A domain name is highly recommended
- An EVE Online Omega Account (Required to make the application, alphas can still use it)

Install
-
Read the Wiki!

Docker
-
1. Clone the repo
2. Copy the config.new.php to config.php
3. Edit config.php
4. Install/Update with composer: `composer install -o` or `composer update -o`
5. Make sure you have docker and docker-compose installed
6. Run `docker-compose up` in the main directory, this will build and start the container
7. Stop the container (ctrl+c) - and then do `docker-compose start` to start it headlessly
8. ???
9. Celebrate

This will be easier once the minor things are fixed, and Shib adds it to auto building...

Future Plans
-
- This framework could be easily expanded into a full blown auth system (srp, fleet tools, etc..) if the interest is 
there.

Known Issues
-
- Roles added manually are not removed (yet...)

Gratuity
-
Like the features? Send 'Mr Twinkie' some isk and a mail letting me know you're a fan!

---

Credits
- 
Karbowiak for the original idea
