# vagrant-gs

Command-line alias for `vagrant global-status`

## Installation

Make sure you have Vagrant 1.6+ and run:

```
vagrant plugin install vagrant-gs
```

## Usage

```
Usage: vagrant gs
```

## Examples

Destroy without confirmation:

```
$ vagrant gs
id       name   provider state  directory
--------------------------------------------------------------------
There are no active Vagrant environments on this computer! Or,
you haven't destroyed and recreated Vagrant environments that were
started with an older version of Vagrant.
```
