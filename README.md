# Dive CRD's

This repo is a small proof of concept based on a [feature request](https://community.dive.co/feature-requests/p/slo-assignment-to-deployments) for [dive.co.](https://dive.co).

The [`./resources`](./resources) dir contains the CRD definitions that can be applied to a cluster to then enable the new resources to be created.

The [`./examples`](./examples) dir contains the new resources that can be created on the cluster.

It is safe to apply these to a running cluster as they do not currently do anything.
