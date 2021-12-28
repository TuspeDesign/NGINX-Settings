# NGINX config

NGINX does not support the Brotli and PageSpeed modules by default, so here's a complete NGINX installation with a script to activate them.

Run `mod-preinstall` before upgrading NGINX or add `mod-apt` to the apt system if using Debian / Ubuntu.

```Shell
ln -s /etc/nginx/mod-apt /etc/apt/apt.conf.d/05nginxmodules
```

- [Adding Brotli to an Already-built NGINX Instance](https://www.majlovesreg.one/adding-brotli-to-a-built-nginx-instance)
- [Adding PageSpeed to an Already-running NGINX Instance](https://www.majlovesreg.one/adding-pagespeed-to-a-running-nginx-instance)
- [PageSpeed Admin Pages](https://www.modpagespeed.com/doc/admin)
- [7 Tips for NGINX Performance Tuning](https://sysopstechnix.com/7-tips-for-nginx-performance-tuning/)
