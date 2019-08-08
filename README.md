
# puppet-ts

#### Table of Contents

1. [Description](#description)
2. [Setup - The basics of getting started with ts](#setup)
    * [What ts affects](#what-ts-affects)
    * [Setup requirements](#setup-requirements)
    * [Beginning with ts](#beginning-with-ts)
3. [Usage - Configuration options and additional functionality](#usage)
4. [Limitations - OS compatibility, etc.](#limitations)

## Description

Puppet module for installing and configuring the LSST Telescope & Site (TS) CSC(s).

## Setup

### What ts affects

The module installs prerequisites, installs the Telescope & Site software, and configures firewall settings.

### Setup Requirements

This module requires the following puppet modules to be installed:

  * https://github.com/LSST-IT/puppet-sal
  * https://github.com/LSST-IT/puppet-python3
  * https://forge.puppet.com/puppetlabs/firewall
  * https://forge.puppet.com/puppetlabs/stdlib

### Beginning with ts

## Usage

To load the TS puppet module, declare this class in your manifest with `include ts`.

## Reference

The following parameters let you extend TS options beyond the default:

  * _tbd_

## Limitations

This TS module only supports RHEL/CentOS servers that are configured to use `iptables`.

