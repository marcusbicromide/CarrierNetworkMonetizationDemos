# Project - Carrier Network Monetization Demos
This Project provides opinions and demonstrations of products made possible (in part) by 5G networks.

![NM](https://user-images.githubusercontent.com/17487052/100970737-9ade8c80-3589-11eb-9ab7-cc02117bddc6.JPEG)
```
Image by DRAW.IO
```

## Getting Started

This project uses the Kubernetes Operator Pattern, to oversee installation, updates, and lifecycle management of the associated services required to run each demonstration on a Kubernetes cluster. 

These consist of:
```
xxxx
```

### Prerequisites

A few requirements need to be met before you can begin:
```
Kubernetes cluster, or derivative (such as OpenShift) based on Kubernetes 1.10 or greater
Access to an Kubernetes cluster, or derivative using an account with cluster-admin permissions
kubectl (or oc) client utility installed
kubevirt-operator installed
External GIT
External Patch Management
```

### Installing

Installation is a simple Kubernetes Operator Install Process (GUI steps below):

```
Navigate in the web console to the Catalog → OperatorHub page
Scroll, or type a keyword into the Filter by keyword box
Select the Operator
Read the information about the Operator and click Install
  On the Create Operator Subscription page:
    Select one of the following:
      All namespaces on the cluster (default) installs the Operator in the default openshift-operators namespace to watch and be made available to all namespaces in the cluster. This option is not always available
      A specific namespace on the cluster allows you to choose a specific, single namespace in which to install the Operator. The Operator will only watch and be made available for use in this single namespace
Select an Update Channel
Select Automatic or Manual approval strategy
Click Subscribe to make the Operator available to the selected namespaces on the cluster
From the Catalog → Operator Management page, you can monitor an Operator Subscription’s installation and upgrade progress

```

## Contributing

The first step is to:
```
File an issue
Find something to work on
Open a pull request
```

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details

## Acknowledgments

Life, the universe and everything.
