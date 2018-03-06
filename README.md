# Helm Charts

**Repository for useful [Helm](https://github.com/kubernetes/helm) charts not part of the [official repositories](https://github.com/kubernetes/charts/).**


This repository follows the same pattern for chart versioning and lifecycle: charts start their life in the
incubator repository. Once they reach an acceptable stability, they get moved to the stable repository.


## Usage

Install the repositories:

```bash
$ helm repo add webplates http://charts.webplates.org/stable/
$ helm repo add webplates-incubator http://charts.webplates.org/incubator/
$ helm repo update
```

Install a chart:

```bash
$ helm repo install webplates/[CHART]
```

## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.
