Apache 2 Reverse Proxy Setup

- Requires: 

  Apache 2 	(httpd/apache2)
  Modules 	(httpd-tools/apache2-utils)
          	(mod_proxy_html/?)
- Usage:

Use the htpasswd binary to create whatever user accounts you want to
allow access to the site behind your proxy.  Default setup shown allows
all authenticated users access.  Further refinements can be added as 
needed.

Simply install the required packages and clone the appropriate folder
to your server, adjust account/path/port settings as needed, and restart 
Apache 2!

- Notes:
  SELinux, If enabled will block Apache from making local connections.

To disable this behavior:

TBD...
