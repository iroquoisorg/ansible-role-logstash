# logstash

[![Build Status](https://travis-ci.com/iroquoisorg/ansible-role-logstash.svg?branch=master)](https://travis-ci.com/iroquoisorg/ansible-role-logstash)

Ansible role for logstash

This role was prepared and tested for Ubuntu 16.04.

# Installation

`$ ansible-galaxy install iroquoisorg.logstash`

# Default settings

```
logstash_version: "2.3"
logstash_syslog_port: 5044
logstash_localsyslog_port: 5000
logstash_es_port: 9200
logstash_key_id: 'D88E42B4'
logstash_heap_size: '1g'
logstash_output_gelf_port: 12201
logstash_output_es: false
logstash_congestion_threshold: 5
```

# Development

Please check [development guide](DEVELOPMENT.md) for details about developing and testing this role.
