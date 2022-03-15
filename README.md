# Terminus CSE tools Plugin

[![Unofficial](https://img.shields.io/badge/Pantheon-Unofficial-yellow?logo=pantheon&color=FFDC28)](https://pantheon.io/docs/oss-support-levels#unofficial)

[![Terminus v1.x Compatible](https://img.shields.io/badge/terminus-v1.x-green.svg)](https://github.com/pantheon-systems/terminus-secrets-plugin/tree/1.x)

A tool for CSE to sweep/clean their dashboard by removing thememselves to the customer's site and delete owned frozen site.

Learn more about Terminus and Terminus Plugins at:
[https://pantheon.io/docs/terminus/plugins/](https://pantheon.io/docs/terminus/plugins/)

## Configuration

This plugin requires no configuration to use.

## Commands

### sweep:sites

Remove self from all the sites that I am not the owner.
```
terminus sweep:sites
```

### sweep:frozen

Delete all owned sites that are frozen.
```
terminus sweep:frozen
```


## Installation
For help installing, see [Manage Plugins](https://pantheon.io/docs/terminus/plugins/)
```
mkdir -p ~/.terminus/plugins
cd ~/.terminus/plugins
git clone https://github.com/pantheon-systems/terminus-sweeper.git
```

In Terminus 3, you can install this plugin by running:
```
terminus self:plugin:install geraldvillorente/terminus-sweeper
```