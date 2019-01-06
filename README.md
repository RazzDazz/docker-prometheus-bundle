# Container for prometheus to run on a synology nas including 
- node exporter
- snmp exporter

## Using instructions from
https://www.digitalocean.com/community/tutorials/how-to-install-prometheus-on-ubuntu-16-04
https://www.robustperception.io/snmp-monitoring-with-prometheus

## Exposed ports:
- 9090

## Volumes
- config directory: `/opt/prometheus`
- data directory: `/var/lib/prometheus`
- log directory: `/var/log/supervisor`

## Sample directory structure on host
```
-- prometheus
    |-- config
    |-- data
    |-- log (optional)
