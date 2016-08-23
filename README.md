CentOS sig-cloud instance build wrapper
=======================================

!["Prompt"](https://raw.githubusercontent.com/gbraad/assets/gh-pages/icons/prompt-icon-64.png)


Build wrapper for [CentOS sig-cloud](https://gitlab.com/gbraad/centos-sig-cloud-instance-images)[*](https://github.com/gbraad/centos-sig-cloud-instance-images) instance images.


Usage
-----

### Cloned

  * CentOS base (7)  
    `docker pull registry.gitlab.com/gbraad/centos:7`


### Custom

  * CentOS 7 (systemd base)  
    `FROM registry.gitlab.com/gbraad/centos:systemd`
  * CentOS 7 - Apache (systemd)  
    `docker run -ti -v /sys/fs/cgroup:/sys/fs/cgroup:ro -v $PWD:/var/www/html:ro -p 80:80 registry.gitlab.com/gbraad/centos:apache`


Authors
-------

| [!["Gerard Braad"](http://gravatar.com/avatar/e466994eea3c2a1672564e45aca844d0.png?s=60)](http://gbraad.nl "Gerard Braad <me@gbraad.nl>") |
|---|
| [@gbraad](https://twitter.com/gbraad)  |
