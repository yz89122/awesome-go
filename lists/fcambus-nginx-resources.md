# Nginx Resources [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A collection of resources covering Nginx, Nginx + Lua, OpenResty and Tengine.

This list is maintained by [Frederic Cambus](https://www.cambus.net). For updates, follow me on Twitter: [@fcambus](https://twitter.com/fcambus)

## Understanding Nginx

- [History of Nginx](https://www.nginx.com/wp-content/uploads/2014/11/Infographic_History-of-Nginx_FulI_20141101.png)
- [Understanding Nginx versioning](https://www.nginx.com/blog/nginx-1-6-1-7-released/)
- [Interview with the creator of Nginx](https://web.archive.org/web/20180614224054/http://mindend.com/interview-with-the-creator-of-nginx/)
- [Interview with Igor Sysoev, author of Apache's competitor NGINX](http://freesoftwaremagazine.com/articles/interview_igor_sysoev_author_apaches_competitor_nginx/)
- [The case for Nginx in front of application servers](https://www.cambus.net/the-case-for-nginx-in-front-of-application-servers/)
- [Nginx Optimization: understanding sendfile, tcp_nodelay and tcp_nopush](https://thoughts.t37.net/nginx-optimization-understanding-sendfile-tcp-nodelay-and-tcp-nopush-c55cdd276765)

## Architecture

- [The Architecture of Open Source Applications (Volume 2): nginx](https://aosabook.org/en/nginx.html)
- [Nginx Guts - Shedding light on Nginx internals](http://www.nginxguts.com/category/nginx/)
- [Nginx discovery journey](https://www.nginx-discovery.com/)
- [Nginx Internals](https://www.slideshare.net/joshzhu/nginx-internals)
- [Inside NGINX: How We Designed for Performance & Scale](https://www.nginx.com/blog/inside-nginx-how-we-designed-for-performance-scale/)
- [Thread Pools in NGINX](https://www.nginx.com/blog/thread-pools-boost-performance-9x/)

## Configuration

- [Beginner's Guide](https://nginx.org/en/docs/beginners_guide.html)
- [Alphabetical index of variables](https://nginx.org/en/docs/varindex.html)
- [Nginx Pitfalls](https://www.nginx.com/resources/wiki/start/topics/tutorials/config_pitfalls/)
- [Useful Rewrites for Nginx](https://blog.engineyard.com/useful-rewrites-for-nginx)
- [Nginx Configuration Primer](https://blog.martinfjordvald.com/nginx-primer/)
- [Nginx Primer 2: From Apache to Nginx](https://blog.martinfjordvald.com/nginx-primer-2-from-apache-to-nginx/)
- [Understanding the Nginx Configuration Inheritance Model](https://blog.martinfjordvald.com/understanding-the-nginx-configuration-inheritance-model/)
- [Nginx HTTP server boilerplate configs ![GitHub Repo Stars](https://img.shields.io/github/stars/h5bp/server-configs-nginx) ![GitHub last commit](https://img.shields.io/github/last-commit/h5bp/server-configs-nginx)](https://github.com/h5bp/server-configs-nginx)
- [Nginx Boilerplate - Configuration template and a set of handy must-have snippets ![GitHub Repo Stars](https://img.shields.io/github/stars/nginx-boilerplate/nginx-boilerplate) ![GitHub last commit](https://img.shields.io/github/last-commit/nginx-boilerplate/nginx-boilerplate)](https://github.com/nginx-boilerplate/nginx-boilerplate)
- [How to Configure OCSP Stapling in Apache and Nginx](https://sslmate.com/blog/post/ocsp_stapling_in_apache_and_nginx)
- [NGINX Config - Online nginx configuration generator](https://www.digitalocean.com/community/tools/nginx)
- [Nice nginx features for developers](https://alex.dzyoba.com/blog/nginx-features-for-developers/)
- [Nice nginx features for operators](https://alex.dzyoba.com/blog/nginx-features-for-operators/)
- [Avoiding the Top 10 NGINX Configuration Mistakes](https://www.nginx.com/blog/avoiding-top-10-nginx-configuration-mistakes/)
- [Gixy - Nginx configuration static analyzer ![GitHub Repo Stars](https://img.shields.io/github/stars/yandex/gixy) ![GitHub last commit](https://img.shields.io/github/last-commit/yandex/gixy)](https://github.com/yandex/gixy)
- [Nginx common configuration - Universal config and snippets ![GitHub Repo Stars](https://img.shields.io/github/stars/tldr-devops/nginx-common-configuration) ![GitHub last commit](https://img.shields.io/github/last-commit/tldr-devops/nginx-common-configuration)](https://github.com/tldr-devops/nginx-common-configuration)

## Tutorials

- [NGINX and NGINX Plus Admin Guide](https://docs.nginx.com/nginx/admin-guide/)
- [agentzh's Nginx Tutorials](https://openresty.org/download/agentzh-nginx-tutorials-en.html) ([Source ![GitHub Repo Stars](https://img.shields.io/github/stars/openresty/nginx-tutorials) ![GitHub last commit](https://img.shields.io/github/last-commit/openresty/nginx-tutorials)](https://github.com/openresty/nginx-tutorials))
- [Introduction to nginx.conf scripting](https://agentzh.org/misc/slides/nginx-conf-scripting/nginx-conf-scripting.html)
- [Load Balancing with NGINX and NGINX Plus](https://www.nginx.com/blog/load-balancing-with-nginx-plus/) ([Part 2](https://www.nginx.com/blog/load-balancing-with-nginx-plus-part-2/))
- [Optimizing Nginx for High Traffic Loads](https://blog.martinfjordvald.com/optimizing-nginx-for-high-traffic-loads/)
- [NGINX as a WebSockets Proxy](https://www.nginx.com/blog/websocket-nginx/)
- [HTTP Keepalive Connections and Web Performance ](https://www.nginx.com/blog/http-keepalives-and-web-performance/)
- [CORS on Nginx](https://enable-cors.org/server_nginx.html)
- [Serving precompressed content with Nginx and Zopfli](https://www.cambus.net/serving-precompressed-content-with-nginx-and-zopfli/)
- [Nginx on FreeBSD](https://www.cambus.net/nginx-on-freebsd/)
- [Using New Debugging Features to Probe NGINX Internals](https://www.nginx.com/blog/new-debugging-features-probe-nginx-internals/)
- [Performing A/B Testing with NGINX and NGINX Plus](https://www.nginx.com/blog/performing-a-b-testing-nginx-plus/)
- [Improving NGINX Performance with Kernel TLS and SSL_sendfile()](https://www.nginx.com/blog/improving-nginx-performance-with-kernel-tls/)

## Modules development

- [Official Development Guide](https://nginx.org/en/docs/dev/development_guide.html)
- [Guide to Nginx Module Development](https://www.evanmiller.org/nginx-modules-guide.html)
- [Advanced Topics In Nginx Module Development](https://www.evanmiller.org/nginx-modules-guide-advanced.html)

## APIs

- [Telize - JSON IP and GeoIP REST API (IP Geolocation) built on Nginx and Lua](https://www.telize.com)
- [GIN - JSON-API framework](http://gin.io/)
- [Outbound API rate limits: the nginx way](https://www.monterail.com/blog/2011/outbound-api-rate-limits-the-nginx-way)
- [Using Nginx to comply with a third-party API's rate limits](https://vitobotta.com/2014/01/12/nginx-rate-limits/)
- [Kong - Management Layer for Microservices and APIs](https://konghq.com/kong/)

## Hacks

- [Nginx JSON hacks](https://web.archive.org/web/20140921162448/http://www.gabrielweinberg.com/blog/2011/07/nginx-json-hacks.html)
- [Using Environment Variables In Nginx.conf](https://web.archive.org/web/20170712003702/https://docs.apitools.com/blog/2014/07/02/using-environment-variables-in-nginx-conf.html)
- [Log rotation directly within Nginx configuration file](https://www.cambus.net/log-rotation-directly-within-nginx-configuration-file/)
- [Realtime pixel tracking with Nginx, syslog-ng, and Redis](https://benwilber.github.io/nginx/redis/syslog/pixel-tracking/2013/09/13/realtime-pixel-tracking-with-nginx-syslog-ng-and-redis.html)
- [Dynamic log formats in Nginx](https://benwilber.github.io/nginx/syslog/logging/2015/08/26/dynamic-log-formats-in-nginx.html)
- [Capture and delay unwanted requests ![GitHub Repo Stars](https://img.shields.io/github/stars/p0pr0ck5/lua-resty-tarpit) ![GitHub last commit](https://img.shields.io/github/last-commit/p0pr0ck5/lua-resty-tarpit)](https://github.com/p0pr0ck5/lua-resty-tarpit)
- [Nginx: a caching, thumbnailing, reverse proxying image server?](https://charlesleifer.com/blog/nginx-a-caching-thumbnailing-reverse-proxying-image-server-/)

## Tips

- [Things you didn't know Nginx could do](https://www.slideshare.net/sarahnovotny/5-things-you-didnt-know-nginx-could-do)
- [Finding the nginx gzip_comp_level sweet spot](https://mjanja.ch/2015/03/finding-the-nginx-gzip_comp_level-sweet-spot/)
- [nginx mirroring tips and tricks](https://alex.dzyoba.com/blog/nginx-mirror/)

## Nginx + Lua

- [Nginx, Lua, and beyond](https://agentzh.org/misc/slides/nginx-lua-and-beyond.pdf)
- [Pushing Nginx to its limit with Lua](https://blog.cloudflare.com/pushing-nginx-to-its-limit-with-lua/)
- [Adding OAuth Support to Nginx via Lua](https://chairnerd.seatgeek.com/oauth-support-for-nginx-with-lua/)
- [Scripting libdrizzle with Lua inside Nginx](https://agentzh.org/misc/slides/libdrizzle-lua-nginx.pdf)
- [Nginx and Lua](https://web.archive.org/web/20141223070856/http://devblog.mixlr.com/2012/09/01/nginx-lua/)
- [Writing an Nginx authentication module in Lua](https://www.stavros.io/posts/writing-an-nginx-authentication-module-in-lua/)
- [Scaling TextRazor in the Cloud with Nginx and Lua](https://www.textrazor.com/blog/2013/03/scaling-textrazor-in-the-cloud-with-nginx-and-lua.html)
- [LSSO - Lua + Nginx SSO System with an OAuth Backend ![GitHub Repo Stars](https://img.shields.io/github/stars/pirogoeth/lsso) ![GitHub last commit](https://img.shields.io/github/last-commit/pirogoeth/lsso)](https://github.com/pirogoeth/lsso)
- [Measuring Nginx Cache Performance using Lua and Redis](https://charlesleifer.com/blog/measuring-nginx-cache-performance-using-lua-and-redis/)
- [nginx-lua - Nginx 1.19+ with LUA support based on Alpine Linux, Amazon Linux, CentOS, Debian, Fedora and Ubuntu. ![GitHub Repo Stars](https://img.shields.io/github/stars/fabiocicerchia/nginx-lua) ![GitHub last commit](https://img.shields.io/github/last-commit/fabiocicerchia/nginx-lua)](https://github.com/fabiocicerchia/nginx-lua)

## Nginx + njs
- [njs scripting language reference and examples](https://nginx.org/en/docs/njs/)
- [Collection of njs use cases ![GitHub Repo Stars](https://img.shields.io/github/stars/f5devcentral/nginx-njs-usecases) ![GitHub last commit](https://img.shields.io/github/last-commit/f5devcentral/nginx-njs-usecases)](https://github.com/f5devcentral/nginx-njs-usecases)
- [JavaScript embedded on NGINX - Getting started with njs](https://www.bluedoa.com/javascript-embedded-on-nginx-getting-started-with-njs/)
- [Create Nginx extensions in JavaScript](https://dev.to/metal3d/create-nginx-extensions-in-javascript-3310)
- [Make your nginx config even more modular and reusable with njs 0.7.7](https://www.nginx.com/blog/make-nginx-config-even-more-modular-reusable-njs-0-7-7/)
- [Diagnostic logging with the NGINX JavaScript module](https://www.nginx.com/blog/diagnostic-logging-nginx-javascript-module/)
- [How to log request headers with NGINX and njs](https://wildwolf.name/how-to-log-request-headers-with-nginx-and-njs/)
- [Using NGINX as an Object Storage Gateway via njs](https://www.nginx.com/blog/using-nginx-as-object-storage-gateway/)
- [Easy HTTPS with NGINX and ACME via njs](https://steinkamp.us/posts/2023-08-10_easy-https-with-nginx)

## OpenResty

- [OpenResty - Fast web app server by extending Nginx](https://openresty.org/en/)
- [Lapis - A web framework for Lua or MoonScript powered by OpenResty](https://leafo.net/lapis/)
- [Nginx image processing server with OpenResty and Lua](https://leafo.net/posts/creating_an_image_server.html)
- [Building an OpenResty events server ![GitHub Repo Stars](https://img.shields.io/github/stars/cagerton/dropthat) ![GitHub last commit](https://img.shields.io/github/last-commit/cagerton/dropthat)](https://github.com/cagerton/dropthat/)
- [SysAdvent 2014 - OpenResty, Nginx and Lua](https://sysadvent.blogspot.com/2014/12/day-22-largely-unappreciated.html) ([Source ![GitHub Repo Stars](https://img.shields.io/github/stars/lusis/sysadvent-2014) ![GitHub last commit](https://img.shields.io/github/last-commit/lusis/sysadvent-2014)](https://github.com/lusis/sysadvent-2014))
- [Ceryx - A dynamic reverse proxy](https://ide.sourcelair.com/blog/articles/75/ceryx-dynamic-nginx)
- [An Introduction To OpenResty](https://openmymind.net/An-Introduction-To-OpenResty-Nginx-Lua/)
- [Programming OpenResty (written by the OpenResty creator)](https://openresty.gitbooks.io/programming-openresty/content/)
- [VeryNginx - Nginx distribution which provides WAF, Control Panel, and Dashboards ![GitHub Repo Stars](https://img.shields.io/github/stars/alexazhou/VeryNginx) ![GitHub last commit](https://img.shields.io/github/last-commit/alexazhou/VeryNginx)](https://github.com/alexazhou/VeryNginx)

## Tengine

- [Tengine Web Server](https://tengine.taobao.org)
- [Difference between OpenResty and Tengine ![GitHub Repo Stars](https://img.shields.io/github/stars/openresty/openresty) ![GitHub last commit](https://img.shields.io/github/last-commit/openresty/openresty)](https://github.com/openresty/openresty/issues/54)

## Talks

- [NGINX Conference 2019 Videos](https://www.youtube.com/playlist?list=PLGz_X9w9raXflDvBv642YFqT0UTqQGFsH)
- [NGINX Conference 2018 Videos](https://www.youtube.com/playlist?list=PLGz_X9w9raXe_Vc708VKvr5KJ4gnf1WxS)
- [NGINX Conference 2017 Videos](https://www.youtube.com/playlist?list=PLGz_X9w9raXeT-z_rcZ9yF0kV5SENZ-yt)
- [NGINX Conference 2016 Videos](https://www.youtube.com/playlist?list=PLGz_X9w9raXcOsB_dT26iu0BvbSxWYG1g)
- [NGINX Conference 2015 Videos](https://www.youtube.com/playlist?list=PLGz_X9w9raXdED9BR6GQ61A6d3fBzjpbn)
- [NGINX Conference 2014 Videos](https://www.youtube.com/playlist?list=PLGz_X9w9raXewvc6tjIGGFZ6DBKHEld3k)
- [NGINX Conference](https://www.nginx.com/nginxconf/)
- [NGINX User Summit 2014 - Lightning talks](https://www.youtube.com/playlist?list=PLGz_X9w9raXfTnRnI6Xl0LMhAKoTVVZv8)

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Frederic Cambus](https://www.cambus.net) has waived all copyright and related or neighboring rights to this work.
