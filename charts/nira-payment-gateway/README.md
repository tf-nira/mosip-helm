# Payments Stage

Helm chart for installing Registration Processor Payments stage.

## Install
```console
$ kubectl create namespace payments
$ helm repo add nira https://niragit.github.io
$ helm -n payments install my-release mosip/nira-payment-gateway
```

