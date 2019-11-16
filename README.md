---

# ansible-linux-nginx

<img src="https://www.ansible.com/hubfs/2016_Images/Assets/Ansible-Mark-Large-RGB-Pool.png?hsLang=en-us" width="10%" height="10%" alt="Ansible logo" align="right"/>

[![License](https://img.shields.io/github/license/autobuilder/ansible-linux-nginx)](https://opensource.org/licenses/MIT)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/autobuilder/ansible-linux-nginx/issues)
[![Build Status](https://travis-ci.org/autobuilder/ansible-linux-nginx.svg?branch=master)](https://github.com/autobuilder/ansible-linux-nginx)

![Platform](https://img.shields.io/badge/platform-ubuntu-dd4814.svg?style=flat) 
![Platform](https://img.shields.io/badge/platform-debian-a80030.svg?style=flat) 
![Platform](https://img.shields.io/badge/platform-centos-932279.svg?style=flat)

Ansible role for install [Nginx][nginx].

---

### Requirements:

* None

### Dependencies:

* None

---

### Variables:

| Variable Name | Default Vaule                             | Description               |
|:--------------|:------------------------------------------|:--------------------------|
|type           | ```_```                                   | _                         |

---

### Example Playbook:

```yaml
- hosts: servers
  roles:
    - ansible-linux-nginx
```

---

### Test Automation:

Automated tests run with [Kitchen-CI][kitchenci] and [Ansible Lint][ansiblelint].
Tested platforms are the below linux-based distros:

* Ubuntu 16.04
* Ubuntu 18.04
* Debian 9
* Centos 7

---

#### License:

This project is made available under the terms of the [MIT][mit].

See the [LICENSE][license] file that accompanies this distribution for the full text of the license.

---

#### Author Information:

[AutoBuilder][autobuilder]

[autobuilder]: https://github.com/autobuilder
[mit]: https://opensource.org/licenses/MIT
[license]: https://github.com/autobuilder/ansible-linux-nginx/blob/master/LICENSE
[ansiblelint]: https://docs.ansible.com/ansible-lint/
[kitchenci]: https://kitchen.ci
[nginx]: https://www.nginx.com/