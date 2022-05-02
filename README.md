# Kustomize patching example

This repository accompanies my answer on <https://stackoverflow.com/q/72086055/147356>.

To build use the `strategicMerge` patch:

```
kustomize build overlay/strategicmerge
```

To build using the JsonPatch patch:

```
kustomize build overlay/jsonpatch
```
