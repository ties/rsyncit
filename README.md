# rsyncit

RRDP -> rsync simple tool

# Running locally

At the moment config file is intentionally left out and configuration is set using CLI options or ENV
These are working values for running sync job every 10 minutes
```-
-DrrdpUrl=https://rrdp.ripe.net/notification.xml -DrsyncPath=/tmp 
```
There are other parameters in `AppConfig` class, but they have reasonable defaults and not necessary for testing.
    
