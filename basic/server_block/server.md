# Server command related commands
### server
> We can declare a server block that will contain one application server configurations, like port, root and etc

- listen
  * `default_server` it's the fallback when no configuration is available
- server_name
  It's useful when two sites listen the same port
- root
- index
- location
  * location directive can include another location directive
  - location
  - try_files
  - autoindex
    * if set to `autoindex on`, we can browser server files on website.
  - internal
- error_page
- access_log
- error_log