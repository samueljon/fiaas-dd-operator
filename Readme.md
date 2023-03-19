# Proof of Concept Operator for FIAAS Deploy Deamon

This is a proof of concept of using the Operator SDK to create an operator from HELM chart.

Initial contents of this operator was created via:

```shell
operator-sdk init --plugins=helm.sdk.operatorframework.io/v1 \
      --domain=fiaas.schibsted.io \
      --group=charts \
      --version=v1alpha1 \
      --helm-chart=fiaas/fiaas-deploy-daemon
```
