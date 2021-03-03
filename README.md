# k8sconnector-snapshot-helm

## Lint the chart

        $ helm lint restorehub-snapshot/*
        // $ helm lint restorehub-snapshot/ # for Windows

## Change chart version

Bump the Chart.version in Chart.yaml. For example from 0.1.0 to 0.1.1

## Generate a new package

        $ helm package restorehub-snapshot/*
        // $ helm package restorehub-snapshot/ # for Windows

## Reindex a package index file

        $ helm repo index --url https://restorehub.github.io/k8sconnector-snapshot-helm/ .

## Push the changes

Make git add/commit/push
