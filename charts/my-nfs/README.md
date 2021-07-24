# my-nfs

** In progress **

Helper chart for quickly creating PVs, PVCs, and initial folders in Kubernetes.

In my personal setup I run Flux, so this allows me to define volumes to be mounted in a consistent and quick way. It also auto creates folders that don't exist, something I wish nfs mounts could be configured to do.

## Test
Test local changes to this with:
```bash
helm template --dry-run my-nfs . -f test_values.yaml
```
