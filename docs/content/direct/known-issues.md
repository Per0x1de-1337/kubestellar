# Some known problems

Here are some user and/or environment problems that we have seen.

For bugs, see [the issues on GitHub](https://github.com/kubestellar/kubestellar/issues) and the [release notes](release-notes.md).

## Wrong value stuck in hidden kflex state in kubeconfig

The symptom is `kflex ctx ...` commands failing. See [Confusion due to hidden state in your kubeconfig](knownissue-kflex-extension.md).

## Kind clusters failing to work

The symptom is `kind` cluster(s) that get created but fail to get their job done. See [Potential Error with Kubestellar Installation related to Issues with Kind backed by Rancher Desktop](knownissue-kind-config.md).

## Authorization fail for Helm fetching chart from ghcr

The symptom is that attempting to instantiate the core Helm chart gets an authorization failure. See [Authorization failure while fetching Helm chart from ghcr.io](knownissue-helm-ghcr.md).

## Missing results in a CombinedStatus object

The symptom is a missing entry in the `results` of a `CombinedStatus` object. See [Missing results in a CombinedStatus object](knownissue-collector-miss.md).

## Insufficient CPU for its1 on KinD cluster

The symptom is kind cluster resource capacity being insufficient for its1's `vcluster-0` pod to be scheduled. See [cpu insufficient for its1](knownissue-cpu-insufficient-fort-its1.md)
