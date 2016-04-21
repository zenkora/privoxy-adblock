# privoxy-adblock-plus
This is just Easylist converted into Privoxy rules and actions files. The config files will work on any OS Privoxy runs on.
Just place these files in Privoxy's config directory add them to your Privoxy config like so:
>actionsfile easylist.script.action

>filterfile easylist.script.filter

The config directory can be found in /etc/privoxy on Linux (and other *nixes I assume), /usr/local/etc/privoxy on OS X, and if you use Windows, it's wherever the hell you put it.
