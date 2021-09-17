# openshift-cli-go-files


# Execution of Go template files
```
$ oc get pods -o go-template-file=podlist.gotemplate
```

```
$ oc get operators  -o go-template-file=podlist.gotemplate jsonpath='{range .items[*]}{.status.components.refs[0].kind=="Deployment"}'
```


