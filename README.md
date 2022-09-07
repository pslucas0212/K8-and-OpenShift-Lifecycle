# Kubernetes and OpenShift Lifecycle

[OCP useful links](https://github.com/pslucas0212/OCP-Useful-Links)  

This documents compares the Kubernetes version release and support cycle with that of OpenShift's release and support cycle.  Last update 23 August 2022.  Check official documentaton (see Appendix below) to confirm correct dates before planning any activities.

### OCP Lifceycle Compared to K8s Lifecycle


OCP Version | OCP Release | OPC EOFS | OCP EOM | K8s Version | K8s Release | K8s EOL
------------|-------------|----------|---------|-------------|-------------|-------
4.x | TBD | TBD | TBD |  1.26 | 6 December 2022 | TBD
4.x | TBD | TBD | TBD |  1.25 | 23 August 2022 | 27 Oct 2023
4.11 | 10 Aug 2022 | 4.12 + 3 Mos |10 Feb 2024 | 1.24 | 3 May 2022 |28 Jul 2023
4.10 |10 Mar 2022| 10 Nov 2022 | 10 Sep 2023 | 1.23 | 7 Dec 2021 | 28 Feb 2023
4.9 | 18 Oct 2021 | 10 Jun 2022 |18 Apr 2023| 1.22 | 4 Aug 2021 | 28 Oct 2022
4.8 | 27 Jul 2021 | 27 Jan 2022 | 27 Jan 2023 | 1.21 | 8 Apr 2021 | 28 Jun 2022
4.7 | 24 Feb 2021| 27 Oct 2022 | 24 Aug 2022 | 1.20 | 8 Dec 2020 | 28 Feb 2022
4.6 EUS | 27 Oct 2020 | 24 March 2021 | 27 Oct 2022 | 1.19 | 26 Aug 2020 | 28 Oct 2021

Notes From kubernetes.io:
- The Kubernetes project maintains release branches for the most recent three minor releases (1.24, 1.23, 1.22). (Source: https://kubernetes.io/releases/)
- Kubernetes 1.19 and newer receive approximately 1 year of patch support. (Source: https://kubernetes.io/releases/patch-releases/#support-period)
- Since v1.22 was released in August 2021 Kubernetes makes new releases three times per year. (Source: https://kubernetes.io/blog/2021/07/20/new-kubernetes-release-cadence/)

### Appendix
- [Red Hat OpenShift Container Platform Life Cycle Policy](https://access.redhat.com/support/policy/updates/openshift)
- [What version of the Kubernetes API is included with each OpenShift 4.x release?](https://access.redhat.com/solutions/4870701)
- [Kuberenetes Release History](https://kubernetes.io/releases/#release-history) - Not a Red Hat web site
- [Kuberentes SIG Release Informaton](https://github.com/kubernetes/sig-release/tree/master/releases) - Not a Red Hat web site

