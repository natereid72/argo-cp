# Base Example of Crossplane Repo for Argo CD
/platform contains the XRD, Composition, and Provider configs.

/aks contains an example XR manifest to create an AKS cluster

In a production model, these two directories would reside in separate repositories.

[Blog post that provides some background on this repo](https://vrelevant.net/crossplane-and-gitops-lets-get-to-the-good-stuff/)

_Prior to using this repository, you will need a K8s cluster with Crossplane and Argo CD installed. You will also need to create a ProviderConfig and a secret for the provider to authenticate to your Azure tenant. Directions for all of this are available at Argo CD and Upbound docs. For a fully relaized GitOps model, we could add something like SealedSecrets to also inlcude the ProviderConfig and Secret within the repo. For directions of installing Crossplane and configuring the Azure Provider, see [here](https://crossplane.io/docs/v1.6/reference/install.html#install-crossplane) and [here](https://crossplane.io/docs/v1.6/cloud-providers/azure/azure-provider.html). For directios of installing Argo CD, see [here](https://argo-cd.readthedocs.io/en/stable/getting_started/)._

