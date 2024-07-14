# Caddy Static File Server

This repository contains a simple Caddy webserver configuration to serve some static files. It is designed to work with CaddyDockerProxy, and run on the files.

## Bolt 

The repo has been created because the BoltCMS Doctrine DataFixtures tried accessing a zip file on a BoltCMS URL. However, the certificate is invalid, making the build process crash on an SSL error. So now we're going to host the file ourselves for the time being. 

## Ubuntu AutoInstallation

But it also contains a template for a Ubuntu autoinstall.yml file. That's still a work in progress though.

- https://github.com/canonical/autoinstall-desktop/blob/main/autoinstall.yaml
- https://nsg.cc/post/2024/autoinstall/
- https://linuxconfig.org/how-to-write-and-perform-ubuntu-unattended-installations-with-autoinstall
- https://blog.local-optimum.net/getting-started-with-autoinstall-on-ubuntu-desktop-24-04-lts-147a1defb2de