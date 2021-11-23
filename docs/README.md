# Magic Mirror

[![Build Status](https://jenkins.tino.sh/buildStatus/icon?job=k8s.magic.mirror%2Fmaster)](https://jenkins.tino.sh/job/k8s.magic.mirror/job/master/)
[![k3s](https://img.shields.io/badge/run%20on%20-Raspberry%20Pi-red)](https://gist.github.com/tinoschroeter/fd4c254e93b2fd0c0b584bdcf756e95f)


```
MagicMirror² is an open source modular smart mirror platform. With a growing list of installable modules, the
```

https://github.com/MichMich/MagicMirror


## Basic access authentication

```
htpasswd -c auth admin
kubectl create secret generic basic-auth --from-file=auth
```
