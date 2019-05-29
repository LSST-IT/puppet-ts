
# puppet-atarchiver

#### Table of Contents

1. [Description](#description)
2. [Setup - The basics of getting started with atarchiver](#setup)
    * [What atarchiver affects](#what-atarchiver-affects)
    * [Setup requirements](#setup-requirements)
    * [Beginning with atarchiver](#beginning-with-atarchiver)
3. [Usage - Configuration options and additional functionality](#usage)
4. [Limitations - OS compatibility, etc.](#limitations)

## Description

Puppet module for installing and configuring the LSST ATArchiver CSC.

## Setup

### What atarchiver affects

The module installs prerequisites, installs the ATArchiver software, and configures firewall settings.

### Setup Requirements

This module requires the following puppet modules to be installed:

  * https://github.com/LSST-IT/puppet-sal
  * https://github.com/LSST-IT/puppet-python3
  * https://forge.puppet.com/puppetlabs/firewall
  * https://forge.puppet.com/puppetlabs/stdlib

### Beginning with atarchiver

## Usage

To load the ATArchiver puppet module, declare this class in your manifest with `include atarchiver`.

## Reference

The following parameters let you extend ATArchiver options beyond the default:

  * _tbd_

## Limitations

This ATArchiver module only supports RHEL/CentOS servers that are configured to use `iptables`.

