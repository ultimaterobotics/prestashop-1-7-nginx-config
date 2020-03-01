# prestashop-1-7-nginx-config
An ultimate nginx config for prestashop 1.7 (tested on Prestashop 1.7.6.3, Ubuntu 18.04, nginx 1.14.0, php 7.2)

After several weeks of torturous search for working nginx config for Prestashop 1.7, I finally have it and sharing for the rest of us with the same problem. 
The one in the official Prestashop repository doesn't work for 1.7, at least not on my system. That probably has to do with them migrating to new Symfony version, and there's a lot of changes, especially in rewrites. I had it half-working at first, but later was forced to look for the solution when the combinations change on product pages didn't work.
This one is largely based on this config https://www.servidoresadmin.com/solucionado-configuracion-vhost-para-nginx-de-prestashop-v1-7-x-funcionando/
Thanks a lot to its authors!

