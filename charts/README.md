# usage

1. pull charts
    * ```shell
      helm pull --version 4.9.0 --repo https://ben-wangz.github.io/helm-chart-mirror/charts ingress-nginx
      ```
2. search for charts
    * ```shell
      helm repo add mirror-ben-wangz https://ben-wangz.github.io/helm-chart-mirror/charts
      helm search repo nginx
      ```
    * reference: https://helm.sh/docs/helm/helm_search_repo

