NOTICE
=====
####Dupda is under developing. It doesn't work! Please wait for release version!
####If you want to join, please send [mail] please.
[mail]:mailto:jeyum2@gmail.com

Dupda
=====
Dupda is web development tool for beginner.

Our goal is creating fast web service. and easy to manage without pre-knowledge.

It uses below open-projects.

- Client Side : [polymer], [Bootstrap] with [jQuery]
- Server Side : [Vert.x], [Yoke]
- DB : [Redis(for static resource)], [MongoDB(for big data set)]

[Polymer]:http://www.polymer-project.org/
[jQuery]:http://jquery.com/
[Bootstrap]:http://getbootstrap.com/
[Vert.x]:http://vertx.io/
[Yoke]:http://pmlopes.github.io/yoke/
[Redis(for static resource)]:http://redis.io/
[MongoDB(for big data set)]:http://www.mongodb.org/


How To Run
-----

**Download from github**

```bash
git clone git://github.com/dupda/dupda.git --recursive

cd dupda
#TODO : Auto Configure
open dupda.html
```


Road Map
-----

1. Web IDE

  1) ***Template Creator <-- Current Working***
    - WYSIWYG template page creator with stylish design.
    - Dynamic binding
    - Java script injection
  
  2) Build with Vert.x Module
    - Build 
    - Testing
    - Deploy

  3) Service Manager with Vert.x Module
    - DB manager
    - Web console

2. Vert.x Service Module
  - HTTP Service
      - Routing
      - Authenticate & Session
      - Secure
      - Gzip
  - Managing API
  
3. Distribute & Auto Configure
  - OS Distributor Like APM Installer (e.g. Ubuntu - apt, Arch linux - pacman)

4. Modularization for scalability
  - Module Manager
  
5. Additional Plugin

  - Multi Template
  - Theme Generator
  - MarkDown Editor
  - Optimizer
  - Device Compatibility 
  - And so on...
  

License
-----
MIT License. 
It can be changed later for some reason. But we guarantee free to use.
