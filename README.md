## Optimum WordPress setup using Nginx and Varnish

The instruction for the setup was originally resides at 
[Ewan Leith blog](https://ewan.im/900/10-million-hits-a-day-with-wordpress-using-a-15-server) 
but already been edited due some misunderstanding on W3 Total Cache development status. 
W3 Total Cache is in fact healthy and [continously developed by Frederik Townes](http://wordpress.org/extend/plugins/w3-total-cache/).

## Tutorial

create new 

    $ /etc/nginx/conf.d/drop

replace 

    $ /etc/nginx/conf.d/default.conf

replace 

    $ /etc/varnish/default.vcl
