---
layout: post
title: Setup Laravel Homestead  on Windows
---

### Introduction

Recently I decided to install Laravel Homestead on Windows. It was my first experience with php and Larval was not fun, at least not for me. So this article was purly dedicated for up and running Laravel Homestead. First of all dont get panic, you will be up and running in no time.

### Installing Vagrant and Virtual box

Install lastest version of virutal box from here [Virtual Box](https://www.virtualbox.org/). Do the same for the [Virtual Box](https://www.vagrantup.com/). Dont worry if you have not worked upon the Vagrant, it works.

Note: Please make sure you uninstall any other Virtual Environment like vmplayer or anything else. Alone this will save some time. After installing Virtual Box there should be "VirtualBox Host-Only Network" in Control Panel\Network and Internet\Network Connections. This will save hours of sturggle.

### Installing The Homestead Vagrant Box

Once VirtualBox / VMware and Vagrant have been installed, you should add the  laravel/homestead box to your Vagrant installation using the following command in your terminal. It will take a few minutes to download the box,depending on your Internet connection speed:

```
vagrant box add laravel/homestead
```

### Installing The Homestead Vagrant Box

You may install Homestead by cloning the repository. Consider cloning the repository into a Homestead folder within your "home" directory, as the Homestead box will serve as the host to all of your Laravel projects:

git clone https://github.com/laravel/homestead.git ~/Homestead