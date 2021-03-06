<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [ansible-influxdb](#ansible-influxdb)
  - [Requirements](#requirements)
  - [Role Variables](#role-variables)
  - [Dependencies](#dependencies)
  - [Example Playbook](#example-playbook)
  - [License](#license)
  - [Author Information](#author-information)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# ansible-influxdb

An [Ansible](https://www.ansible.com) role to install/configure [InfluxDB](https://www.influxdata.com/time-series-platform/influxdb/)

## Requirements

None

## Role Variables

[defaults/main.yml](defaults/main.yml)


## Dependencies

None

## Validation

### Dependancies

- [virtualbox](https://www.virtualbox.org/manual/ch02.html)
- [vagrant](https://www.vagrantup.com/docs/installation/)
- [molecule](https://molecule.readthedocs.io/en/latest/installation.html)
- python-vagrant - pip install python-vagrant

### tests

```$ molecule test```
```$ molecule test -s config```

## Example Playbook

[molecule/default/playbook.yml](molecule/default/playbook.yml)

## License

MIT

## Author Information

Larry Smith Jr.

-   [EverythingShouldBeVirtual](http://everythingshouldbevirtual.com)
-   [@mrlesmithjr](https://www.twitter.com/mrlesmithjr)
-   <mailto:mrlesmithjr@gmail.com>
