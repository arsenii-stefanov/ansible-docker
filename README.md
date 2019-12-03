Ansible-Docker
=========

This role installs Docker and Docker-Compose on a server

### Configurable options

> Default values are set in `defaults/main.yml`


### UBUNTU

* docker_version_ubuntu

```
# Example
docker_version_ubuntu: 18.06.1~ce~3-0~ubuntu
```

* docker_packages_ubuntu

```
# Example
docker_packages_ubuntu: [ "docker-ce={{ docker_version_ubuntu }}" ]
```

### DEBIAN

* docker_version_debian

```
# Example
docker_version_debian: 18.06.1~ce~3-0~debian
```

* docker_packages_debian

```
# Example
docker_packages_debian: [ "docker-ce={{ docker_version_debian }}" ]
```

### COMMON

* docker_compose_version - set a Docker-Compose version if you need Docker-Compose on your server, othervise leave this variable blank or ommit it

```
# Example
docker_compose_version: 1.23.2
```
