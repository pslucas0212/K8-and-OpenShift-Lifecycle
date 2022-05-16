# Kubernetes and OpenShift Lifecycle

This documents compares the Kubernetes version release and support cycle with that of OpenShift's release and support cycle.  Last update 16 May 2022.  Check official documentaton (see Appendix below) to confirm correct dates before planning any activities.

### OCP Lifceycle Compared to K8 Lifecycle


OCP Version | OCP Release | OCP EOM | K8s Version | K8s Release | K8s EOL
------------|-------------|---------|------------|------------|-------
4.x | TBD | TBD |  1.25 | 23 August 2022 | TBD
4.x | TBD | TBD | 1.24 | 3 May 2022 |29 September 2023
4.10 |10 March 2022| 10 September 2023 | 1.23 | 7 December 2021 | 28 February 2023
4.9 | 18 October 2021 | 18 April 2023| 1.22 | 4 August 2021 | 28 October 2022
4.8 | 27 July 2921 | 27 January 2023 | 1.21 | 8 April 2021 | 28 June 2022
4.7 | 24 February 2021| 24 August 2022 | 1.20 | 8 December 2020 | 28 February 2022
4.6 EUS | 27 October 2020 | 27 October 2022 | 1.19 | 26 August 2020 | 28 October 2021

Notes from kubernetes.io:
- The Kubernetes project maintains release branches for the most recent three minor releases (1.24, 1.23, 1.22). (Source: https://kubernetes.io/releases/)
- Kubernetes 1.19 and newer receive approximately 1 year of patch support. (Source: https://kubernetes.io/releases/patch-releases/#support-period)
- Since v1.22 was released in August 2021 Kubernetes makes new releases three times per year. (Source: https://kubernetes.io/blog/2021/07/20/new-kubernetes-release-cadence/)

### Appendix

- [Red Hat OpenShift Container Platform Life Cycle Policy](https://access.redhat.com/support/policy/updates/openshift)
- [What version of the Kubernetes API is included with each OpenShift 4.x release?](https://access.redhat.com/solutions/4870701)
- [Kuberenetes Release History](https://kubernetes.io/releases/#release-history) - Not a Red Hat web site
- [Kuberentes SIG Release Informaton](https://github.com/kubernetes/sig-release/tree/master/releases) - Not a Red Hat web site
- [Kubernetes version lifecycle visualization](https://endoflife.date/kubernetes) - Not a Red Hat web site
