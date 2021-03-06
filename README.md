# openhab

[![Build Status](https://travis-ci.org/cyberkov/puppet-openhab.svg?branch=master)](https://travis-ci.org/cyberkov/puppet-openhab)

#### Table of Contents

1. [Overview](#overview)
2. [Module Description - What the module does and why it is useful](#module-description)
3. [Setup - The basics of getting started with openhab](#setup)
    * [What openhab affects](#what-openhab-affects)
    * [Setup requirements](#setup-requirements)
    * [Beginning with openhab](#beginning-with-openhab)
4. [Usage - Configuration options and additional functionality](#usage)
5. [Reference - An under-the-hood peek at what the module is doing and how](#reference)
5. [Limitations - OS compatibility, etc.](#limitations)
6. [Development - Guide for contributing to the module](#development)

## Overview

This module installs openHAB on your machine. 
For now it has been tested with Raspbian 8 but should work on Debian 7 and 8 as well.

## Setup

### What openhab affects

* A list of files, packages, services, or operations that the module will alter,
  impact, or execute on the system it's installed on.
* This is a great place to stick any warnings.
* Can be in list or paragraph form.

### Beginning with openhab

The very basic steps needed for a user to get the module up and running.

If your most recent release breaks compatibility or requires particular steps
for upgrading, you may wish to include an additional section here: Upgrading
(For an example, see http://forge.puppetlabs.com/puppetlabs/firewall).

## Usage

Put the classes, types, and resources for customizing, configuring, and doing
the fancy stuff with your module here.

## Reference

Here, list the classes, types, providers, facts, etc contained in your module.
This section should include all of the under-the-hood workings of your module so
people know what the module is touching on their system but don't need to mess
with things. (We are working on automating this section!)

## Limitations

* Needs a Debian based OS as of now. Installation from source is not supported (yet).

## Development

If you have something to add, please just send me a Pullrequest :-)

