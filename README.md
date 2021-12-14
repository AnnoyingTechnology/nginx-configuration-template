## NGinX configuration template

This offers 
* Bad robots blocking
* Legitimate robots blocking 
* Scanner and script kiddies blocking
* Blocking IPs that don't belong to you 
* HTTP Basic Auth
* Let's encrypt integration
* Assets compression and caching
* PHP-FPM configuration for `5.6`, `7.0`, `7.1`, `7.2`, `7.3`, `7.4`, `8.0`, `8.1` (on demand)
* Munin (monitoring) support
* Three levels of SSL/TLS security to choose from (using different ciphers and minimum tls versions)

It has three sample domains configuration files 
* a public website (allow indexing, etc.)
* a private backend (disallow indexing, block all but your IPs, requires auth, etc.)
* a web application (disallow indexing, block scanner/bots, etc.)

Install nginx (tested on 1.15), copy those configuration files and tweak to your needs.
