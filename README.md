# Nginx Boilerplate 

Selfishly modified version of [nginx-boilerplate](https://github.com/nginx-boilerplate/nginx-boilerplate)

## Beware
This is only for compiled nginx, as the default path is different,
`/usr/local/nginx` as opposed to `/etc/nginx`

## Features
 * Convenient include-based config structure
 * Optimized defaults
 * Connection and requests rate limiting settings
 * Backend response caching
 * Various predefined locations
 * Advanced logging
 
## Requirements
 * `Nginx` >= `1.7`
 * `/etc/hosts` might need changing for local development
 * [headers-more](https://github.com/openresty/headers-more-nginx-module)
 * [ngx_brotli](https://github.com/google/ngx_brotli)

## If something doesn't work
 * Check the contents of the site's access/error logs
 * Make sure to have proper file/folder permissions
 * Create an issue on the project's github page
