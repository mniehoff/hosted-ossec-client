This repository contains several roles to deploy an SIEM agent to a host.
The agent contains
- the wazuh/ossec agent
- a network sniffer, transfering tcpdumps to redis

Both are started as service.

See `site.yml` for an example.

min. ansible version: 2.1
