##Optimum WordPress setup using Nginx and Varnish

The instruction for the setup was originally resides at [http://www.ewanleith.com/blog/900/10-million-hits-a-day-with-wordpress-using-a-15-server](Ewan Leith blog) but already been edited due some misunderstanding on W3 Total Cache development status. W3 Total Cache is in fact healthy and continously developed by Frederik Jones.

##Tutorial

create new 
    $ /etc/nginx/conf.d/drop

replace 
    $ /etc/nginx/conf.d/default.conf

replace 
    $ /etc/varnish/default.vcl

##Alternative

I'm operating managed WordPress hosting loosely based on this setup and if you want affordable high performance WordPress installation without the hassle of server configuration, you can do so at [KittySensei](http://www.kittysensei.com) website.
