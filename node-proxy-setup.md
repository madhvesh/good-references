# Configuring NPM, Node and Bower behind a proxy on windows

This page provides the basic tools and configuration for bootstraping an application with npm and bower behind a proxy on windows. There is still a lot of struggle with setting up your workstation behind a proxy on windows, I am creating this hoping to make it easy for developers to get started scaffolding their apps behind the proxy. It also serves as a cheat sheet for some of the npm packages that can be used to build a responsive application.

Jump to [What's new in 3.2.0?](#changelog)

[Stripe][1] payment gateway.

Target Software (at the time of creation)

* Windows 7+
* Npm 3.6.0 (#Manual)
* Node 5.0+
* Bower 1.4.1
[Stripe][1] Account

Installation

- [Changelog](#changelog)


Manual
  # Install npm
  # Install node 

* Download the Windows installer from the Nodes.js® web site.
* Run the installer (the .msi file you downloaded in the previous step.)
* Follow the prompts in the installer (Accept the license agreement, click the NEXT button a bunch of times and accept the default installation settings).

* Restart your computer. You won’t be able to run Node.js® until you restart your computer.


Open command Prompt as Admin. 
set the proxy in command prompt for npm
npm config set proxy "http://domain\username:password@servername:port/"
npm config set https-proxy "https://domain\username:password@servername:port/"

Install bower

# With chocolatey
Easy Install chocoletey[https://chocolatey.org/]
Install node (also installs npm)
choco install nodejs.install 


Changelog
---------


[1]: http://stripe.com
