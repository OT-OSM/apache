
## Ansible Role: apache
<img src="https://github.com/user-attachments/assets/5bb867e8-8067-446b-89b8-05265962e911" alt="Apache Logo" width="150" height="150"/>



### Version History

|**Date**| **Version**| **Description**| **Changed By** |
|----------|---------|---------------|-----------------|
|**MAY '29'** | V.1 | Initial Draft | Mohit Saini |



## Table of Content
- [Introduction](#introduction)
- [Features](#features)
- [Supported OS](#supported-os)
- [Directory Structure](#directory-structure-of-apache-role )
- [References](#references)


### Introduction

**Apache** HTTP Server is a free, open-source web server developed by the Apache Software Foundation, widely used in web hosting and part of the LAMP stack


### Features

- **.htaccess Support**: Enables per-directory configuration without restarting the server, ideal for shared hosting.
- **Loadable Dynamic Modules**: Allows runtime loading/unloading of features for flexibility and customization.
- **URL Rewriting (mod_rewrite)**: Powerful and flexible URL manipulation for clean URLs and redirects.
- **Extensive Scripting Support**: Supports multiple languages like PHP, Perl, and Lua via modules.
- **Geolocation Based on IP Address**: Delivers location-aware content or restrictions using IP-based detection..

### Supported OS
------------
  * Ubuntu 18.04 and above
  * Debian 11 and above
  * RHEL 7.0 and above

### Directory Structure of apache role 

```
├── defaults
│   └── main.yml
├── handlers
│   └── main.yml
├── meta
│   └── main.yml
├── README.md
├── tasks
│   ├── debian.yml
│   ├── main.yml
│   └── redhat.yml
```



## References
----------
- **[Apache Installation Steps](https://phoenixnap.com/kb/install-apache-ubuntu)**
