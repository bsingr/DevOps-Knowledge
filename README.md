# Cloud Development & Deployment with Docker

## Common

* http://12factor.net/

## Development

Typical tasks:

* Share environments amongst developers
* Spin up multiple services on a single machine
* Develop service internals
* Develop service deployment interface

### Docker on OSX

* boot2docker
  * does not support shared folders right know
* docker-osx
  * soon deprecated?
* Vagrant
  * too much overhead for docker?

### Local Docker Development

* fig
* fig + shipyard
* fig2coreos

## Deployment

Typical tasks:

* Deploy multiple services on single host
* Deploy multiple services on multiple hosts
* Connect services on different hosts with each other
* Rollback deployments
* Migrate data

### Docker

- links
- links + ambassadors (via socat reverse proxying)
- links + ambassadors + serf (for service-discovery)

### CoreOS

- systemd service configuration
- etcd

### Configuration Management

- Chef
- Puppet
- Salt
- Ansible
- CFEngine
- …

## PaaS

### dokku

### Deis

System

- CoreOS

Applications

- Dockerfile
- Heroku-buildpack
- git push

### Flynn

Systems

- etcd
- discoveryd

Applications

- Procfile
- git push

### Others

- ZooKeeper
- Mesos

### Full-fledged

- Cloud Foundry
- OpenShift (RedHat)
- Heroku

