# ansible-pihole-docker-configuration

A simple configuration wrapper for PiHole running in a docker container. The ansible user must be in the docker group.

## Rationale

I use [dockerized PiHole](https://github.com/derekmurawsky/dns-resolution) to serve internal DNS on my network. In order to support configuration of the domains in a sane manner, I put together this role.

## Features

* Supports adding multiple conditional forwarders.
* Supports multiple A records.

## Credits

I pulled a lot of this configuration from [mrlesmithjr/ansible-dnsmasq](https://github.com/mrlesmithjr/ansible-dnsmasq/).

## TODO

* Support Allow/Deny list management - Since I have two PiHole servers I'd like to centrally manage thier lists via this same module.
