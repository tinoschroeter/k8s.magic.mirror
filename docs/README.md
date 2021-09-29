# Magic Mirror

[![Build Status](https://jenkins.tino.sh/buildStatus/icon?job=k8s.magic.mirror%2Fmaster)](https://jenkins.tino.sh/job/k8s.magic.mirror/job/master/)


```
MagicMirror² is an open source modular smart mirror platform. With a growing list of installable modules, the
```

https://github.com/MichMich/MagicMirror


## Basic access authentication

```
htpasswd -c auth admin
kubectl create secret generic basic-auth --from-file=auth
```
