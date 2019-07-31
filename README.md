# unleash-helm

Run a kuberenetes deployment of [unleash](https://github.com/Unleash/unleash) using [helm](https://github.com/helm/charts),
alongside postgresql.

The `templates/` directory contains a very simple deployment resource with a couple of parameters.

The values.yaml file contains the default values for the deployment template as well as the postgres dependency.

## How to run?

1. You will need to have a kubernetes cluster running locally (using `minikube`, for example.) or remotly connected.

2. Follow [these](https://helm.sh/docs/using_helm/#quickstart-guide) instructions to install helm client & server.

3. Checkout this chart - `git checkout https://github.com/nimrodshn/unleash-helm && cd unleash-helm` and run the following:
`helm install .`.
