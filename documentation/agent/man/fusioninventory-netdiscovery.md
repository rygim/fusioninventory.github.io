---
layout: page
title: fusioninventory-netdiscovery
---

# NAME

fusioninventory-netdiscovery - Standalone network discovery

# SYNOPSIS

fusioninventory-netdiscovery \[options\] --first \<start\> --last \<stop\>

    Options:
      --first address IP range first address
      --last address  IP range last address
      --credential    SNMP credential (default: version:1,community:public)
      --entity        GLPI entity
      --threads nb    number of discovery threads (default: 1)
      --timeout val   SNMP timeout (default: 1s)
      --verbose       verbose output (control messages)
      --debug         debug output (execution traces)
      -h --help       print this message and exit
      --version       print the task version and exit

# DESCRIPTION

`fusioninventory-netdiscovery` allows to run a network discovery task without a
GLPI server.
