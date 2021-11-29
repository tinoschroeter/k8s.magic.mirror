# Magic Mirror

[![Build Status](https://jenkins.tino.sh/buildStatus/icon?job=k8s.magic.mirror%2Fmaster)](https://jenkins.tino.sh/job/k8s.magic.mirror/job/master/)
[![k3s](https://img.shields.io/badge/run%20on%20-Raspberry%20Pi-red)](https://github.com/tinoschroeter/k8s.homelab)
[![GitHub Super-Linter](https://github.com/tinoschroeter/k8s.homelab/workflows/Lint%20Code%20Base/badge.svg)](https://github.com/tinoschroeter/k8s.magic.mirror/actions/workflows/linter.yml)


```
MagicMirror² is an open source modular smart mirror platform. With a growing list of installable modules, the
```

https://github.com/MichMich/MagicMirror


## Basic access authentication

```
htpasswd -c auth admin
kubectl create secret generic basic-auth --from-file=auth
```
