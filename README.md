# Buildpack for AngularDart app

This buildpack should be used for serving static files from `web` folder.  
It not make any compiling dart app to js, so should app will work only with Dartium.

## Structure
* `.dartnginx` - buildpack trigger
* `web` - this folder holds all files to be served by nginx
* nginx.conf.erb - configuration for nginx
