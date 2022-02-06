# Base Example of Crossplane Repo for Argo CD
/platform contains the XRD, Composition, and Provider configs.

/aks contains an example XR manifest to create an AKS cluster

Prior to using this repository, you will need a K8s cluster with Crossplane and Argo CD installed. You will also need to create a ProviderConfig and a secret for the provider to authenticate to your Azure tenant. Directions for all of this are available at Argo CD and Upbound docs. For a fully relaized GitOps model, we could add something like SealedSecrets to also inlcude the ProviderConfig and Secret within the repo.

In a production model, these two directories would reside in separate repositories.
