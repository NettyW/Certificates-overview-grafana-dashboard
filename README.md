# Certificates overview grafana dashboard

The dashboard displays information about certificates in Windows.

## The dashboard shows information:
* Certificate name (canonical name) - ***CN***
* Host on which it is located - ***instance***
* Certificate expiration date - ***expire date***
* Short name or - ***thumbprint***
* Public key in **hex** format or - ***pubkey***

## Installing

Import from grafana dashboard with id `22294` or installing with `json` file from this repo.

**or**

Watch on the [grafana dashboards](https://grafana.com/grafana/dashboards/22294-certificates-overviev/) )
---

### The dashboard requires the [windows_certificate_exporter](https://github.com/NettyW/windows_certificate_exporter) to function
