# Sentry helm chart

## Add chart repo
```
helm repo add sentry https://sentry-kubernetes.github.io/charts
```

## Install chart
```
helm install --namespace sentry sentry -f ./value.yml sentry/sentry
```