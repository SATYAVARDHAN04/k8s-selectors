## ADDING LABELS TO A NODE

```bash
kubectl label nodes <node-name> <label-key>=<label-value>
```

## TAINTING A NODE

```bash
kubectl taint nodes <node-name> <taint-key>=<taint-value>:<taint-effect>
```