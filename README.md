# XL Deploy WAS Installer plugin

[![Build Status][xld-was-installer-plugin-travis-image]][xld-was-installer-plugin-travis-url]
[![License: MIT][xld-was-installer-plugin-license-image]][xld-was-installer-plugin-license-url]
![Github All Releases][xld-was-installer-plugin-downloads-image]

[xld-was-installer-plugin-travis-image]: https://travis-ci.org/xebialabs-community/xld-was-installer-plugin.svg?branch=master
[xld-was-installer-plugin-travis-url]: https://travis-ci.org/xebialabs-community/xld-was-installer-plugin
[xld-was-installer-plugin-license-image]: https://img.shields.io/badge/License-MIT-yellow.svg
[xld-was-installer-plugin-license-url]: https://opensource.org/licenses/MIT
[xld-was-installer-plugin-downloads-image]: https://img.shields.io/github/downloads/xebialabs-community/xld-was-installer-plugin/total.svg

## Preface

This document describes the functionality provided by the XL Deploy WAS Installer plugin.

See the [XL Deploy reference manual](https://docs.xebialabs.com/xl-deploy) for background information on XL Deploy and deployment automation concepts.  

## Overview

Installs the WAS binaries on a Linux host.

## Requirements

XLD 7.5+

## Installation

* Copy the latest JAR file from the [releases page](https://github.com/xebialabs-community/xld-was-installer-plugin/releases) into the `XL_DEPLOY_SERVER/plugins` directory.
* Restart the XL Deploy server.

## Usage

Installation default is /opt/IBM/WebSphere/AppServer.

Note:  do not set the log and shared-resources directories to be subdirectories of the installation directory

## References

