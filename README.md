# docker-terrortown

A docker with steam preconfigured inside.  
Configure your `steamcmd.cmd` to run your dedicated server.  


## Disclaimer

This Image is based on the project https://github.com/Micka33/docker-steam


## Dependency

- [Docker](https://www.docker.com/)  
  - [Mac OS X](https://docs.docker.com/installation/mac/)  
  - [Ubuntu](https://docs.docker.com/installation/ubuntulinux/)  
  - [Red Hat Enterprise Linux](https://docs.docker.com/installation/rhel/)
  - [CentOS](https://docs.docker.com/installation/centos/)
  - [Debian](https://docs.docker.com/installation/debian/)
  - [Gentoo](https://docs.docker.com/installation/gentoolinux/)
  - [Google Cloud Platform](https://docs.docker.com/installation/google/)
  - [Rackspace Cloud](https://docs.docker.com/installation/rackspace/)
  - [Amazon EC2](https://docs.docker.com/installation/amazon/)
  - [IBM Softlayer](https://docs.docker.com/installation/softlayer/)
  - [Arch Linux](https://docs.docker.com/installation/archlinux/)
  - [FrugalWare](https://docs.docker.com/installation/frugalware/)
  - [Fedora](https://docs.docker.com/installation/fedora/)
  - [openSUSE](https://docs.docker.com/installation/openSUSE/)
  - [CRUX Linux](https://docs.docker.com/installation/cruxlinux/)
  - [Microsoft Windows](https://docs.docker.com/installation/windows/)

optional

- [Docker Compose](https://www.docker.com/)

## Install it

Without docker-compose:

```bash
git clone https://github.com/bufanda/docker-terrortown.git
cd docker-terrortown
sudo docker build -t bufanda/terrortown ./docker_files
```

With docker-compose:

```bash
git clone https://github.com/bufanda/docker-terrortown.git
cd docker-terrortown
docker-compose build
```

## Run it

Without docker-compose:

Modefiy and use the run script:

```bash
./run.sh start
```

With docker-compose:

```bash
docker-compose up -d
```

## About it

Currently, this docker is configured to run a **Garry's Mod TTT dedicated server**.
