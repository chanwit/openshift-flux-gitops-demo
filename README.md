# openshift-flux-gitops-demo
GitOps demo with Flux v2 on OpenShift

# Steps

Clone this repo
```
$ git clone https://github.com/chanwit/openshift-flux-gitops-demo
```

Log into GitHub using the GH cli
```
$ gh auth login
```

Find your credentials from the GH hosts config
```
$ cat ~/.config/gh/hosts.yaml
```

Install the Flux v2 runtime
```
$ flux bootstrap github 
```
