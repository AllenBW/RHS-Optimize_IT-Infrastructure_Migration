# RHS - Optimize IT - Infrastructure Migration
Red Hat Solutions - Optimize IT - Infrastructure Migration

This is currently work in progress. Please use it with caution.
Please, report issues with documentation and/or lab in the issues section of this repo.

* [Red Hat Product Demo System](https://rhpds.redhat.com)
* [Infrastructure Migration Lab v1 Instructions](docs/00-redhat_solutions-insfrastructure_migration_v1-lab.adoc)

## Releases
```
  0.1 Initial commit
  0.2 Fixed RHV cluster config
  0.3 Added ssh access from workstation to other infra
  0.4 Modified vCenter config
  0.5 Modified ESXi configs 
  0.6 Fixzed networking issues. Static IP for storage and migration
  0.7 Cleaned up resources
  0.8 Fixed cloud-init in workstation
  0.9 Added ansible to workstation
  0.10 Added VMs to vSphere (nginx, jboss0, jboss1, db)
  0.11 Initial playbooks to deploy Nginx and JBoss EAP
  0.12 Playbooks deploy Nginx and JBoss in Domain, also PostgreSQL
  0.13 Reconfigured csv to use current VMs
  0.14 Fixes for nginx config file (https rewrite)
  0.15 Changed nginx VM to lb.example.com. Minor fixes
  0.16 Ticket Monster configured to connect to DB (PostgreSQL)
  0.17 Remove tags in environment. Cleanup logs.
  0.18 Added second RHV Hypervisor. Improved documentation.
  1.0 Go Live!
```
