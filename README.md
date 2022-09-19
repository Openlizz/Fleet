<h1 align="center">Lizz compatible fleet repository</h1>

This repository serves as base for the fleet repository when initializing a Lizz managed Kubernetes cluster with the following command:

```
lizz init github \
  --owner=$GITHUB_USER \
  --destination=fleet \
  --origin-url=https://github.com/openlizz/fleet \
  --personal
```

It describes the infrastructure of the cluster and points to the applications repositories.

To learn more about Lizz, see the [documentation](https://openlizz.com).

## Acknowledgements

This repository is highly inspired by the [multi-tenant cluster repository](https://github.com/fluxcd/flux2-multi-tenancy) of the Flux team.