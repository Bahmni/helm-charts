# Bahmni Helm Charts Repository
## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  `helm repo add bahmni https://bahmni.github.io/helm-charts`


If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  

You can then run `helm search repo bahmni` to see the latest stable charts. You can run `helm search repo bahmni -l --devel` to list all artifacts in the bahmni helm repo.
