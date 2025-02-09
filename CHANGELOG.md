# Docker Image Packaging for Atlassian Confluence

## 6.15.3-0alvistackx - TBC

### Major Changes

## 6.15.3-0alvistack5 - 2019-05-20

### Major Changes

  - Bugfix "Build times out because no output was received"
  - Upgrade minimal Ansible support to 2.8.0

## 6.15.2-0alvistack2 - 2019-04-16

### Major Changes

  - Run systemd service with specific system user
  - Explicitly set system user UID/GID
  - Porting to Molecule based

## 6.13.0-1alvistack1 - 2018-12-10

### Major Changes

  - Update base image to Ubuntu 18.04
  - Revamp deployment with Ansible roles
  - Replace Oracle Java with OpenJDK

## 6.12.1-0alvistack3 - 2018-10-29

### Major Changes

  - Handle changes with patch
  - Update dumb-init to v.1.2.2
  - Upgrade MySQL Connector/J and PostgreSQL JDBC support
  - Add TZ support
  - Add SESSION\_TIMEOUT support

## 6.7.2-0alvistack2 - 2018-03-11

### Major Changes

  - Simplify Docker image naming

## 6.7.1-0alvistack1 - 2018-02-28

  - Migrate from <https://github.com/alvistack/ansible-container-confluence>
  - Pure Dockerfile implementation
  - Ready for both Docker and Kubernetes use cases
