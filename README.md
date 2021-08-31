# victoriametrics-rpm
RPM for VictoriaMetrics - the best long-term remote storage for Prometheus

[![Copr build status](https://copr.fedorainfracloud.org/coprs/antonpatsev/VictoriaMetrics/package/victoriametrics/status_image/last_build.png)](https://copr.fedorainfracloud.org/coprs/antonpatsev/VictoriaMetrics/package/victoriametrics/)

## Installation with yum
Support CentOS 6, CentOS 7, Oraclelinux 7

```
yum -y install yum-plugin-copr

yum copr enable antonpatsev/VictoriaMetrics

yum makecache

yum -y install victoriametrics

systemctl start victoriametrics
```

## Installation with dnf
Support CentOS 8, CentOS-stream 8, CentOS-stream 9, Oraclelinux 8, Fedora 33,34,35

```
dnf -y install yum-plugin-copr

dnf copr enable antonpatsev/VictoriaMetrics

dnf makecache

dnf -y install victoriametrics

systemctl start victoriametrics
```

