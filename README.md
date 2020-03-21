# molecule-docker-images

Dockerfiles used to build a set of images based on Red Hat open distros, ready to be used with Molecule to test Ansible roles.
The images currently available are:

- [centos7-pys](https://hub.docker.com/repository/docker/nmusatti/centos7-pys)
- [centos7-pys-systemd](https://hub.docker.com/repository/docker/nmusatti/centos7-pys-systemd)
- [fedora-pys](https://hub.docker.com/repository/docker/nmusatti/fedora-pys)
- [fedora-pys-systemd](https://hub.docker.com/repository/docker/nmusatti/fedora-pys-systemd)

The CentOS 8 based images aren't currently available, due to a problem with base images:
- [centos8-pys](https://hub.docker.com/repository/docker/nmusatti/centos8-pys)
- [centos8-pys-systemd](https://hub.docker.com/repository/docker/nmusatti/centos8-pys-systemd)

All Dockerfiles are directly derived from those made available by the [Pycontribs](https://github.com/pycontribs) and the
[CentOS-Dockerfiles](https://github.com/CentOS/CentOS-Dockerfiles) projects.
