# Kubernetes and OpenShift Lifecycle


[Table of Contents - Useful Red Hat Links](https://github.com/pslucas0212/UsefulRedHatLinks)
[OCP useful links](https://github.com/pslucas0212/OCP-Useful-Links) 

Updated 26 February 2025

This documents compares the Kubernetes version release and support cycle with that of OpenShift's release and support cycle.  Per Red Hat's OCP lifecycle document linked below "Red Hat aims to forecast these at a 4 month cadence, providing customers ample opportunity to plan."   Check official documentaton (see Appendix below) to confirm correct dates before planning any activities.

Note: OCP Managed Services on Azure and AWS have a different lifecycle.
- [Support lifecycle for Azure Red Hat OpenShift 4](https://learn.microsoft.com/en-us/azure/openshift/support-lifecycle)
- [Red Hat OpenShift Service on AWS update life cycle Overview](https://docs.openshift.com/rosa/rosa_architecture/rosa_policy_service_definition/rosa-life-cycle.html)

#### Other OCP related product lifecycles
- [OpenShift Operator Life Cycles](https://access.redhat.com/support/policy/updates/openshift_operators)
- [Red Hat Advanced Cluster Management for Kubernetes](https://access.redhat.com/support/policy/updates/advanced-cluster-management)
- [Red Hat Advanced Cluster Security for Kubernetes Support Policy](https://access.redhat.com/support/policy/updates/rhacs)
- [Red Hat Quay Life Cycle Policy](https://access.redhat.com/support/policy/updates/rhquay)

### OCP Lifceycle Compared to K8s Lifecycle


OCP Version | OCP Release | OCP EOFS | OCP EOM | OCP EUS | OCP EUS Term 2 |K8s Version | K8s Release | K8s MM | K8s EOL
------------|-------------|----------|---------|---------|----------------|-------------|-------------|--------|--------
4.x | TBD | TBD | TBD | - | - | 1.34 | 27 Aug 2025 | TBD | TBD
4.x | TBD | TBD | TBD | - | - | 1.33 | 23 Apr 2025 | 28 Apr 2026 | 28 Jun 2026
4.19 | 17 Jun 2025 | GA of 4.20 + 3 Months | 17 Dec 2026 | N/A | N/A | 1.32 | 14 Jan 2025 | 28 Dec 2025 | 28 Feb 2026
4.18 | 25 Feb 2025 | 17 Sep 2025 | 25 Aug 2026 | 25 Feb 2027 | 25 Feb 2028 | 1.31 |13 Aug 2024 | 28 Aug 2025 | 28 Oct 2025
4.17 | 1 Oct 2024 | 25 May 2025 | 1 Apr 2026 | N/A | N/A | 1.30 |17 Apr 2024 | 28 Apr 2025 | 28 Jun 2025
4.16 | 27 Jun 2024 | 1 Jan 2025 | 27 Dec 2025 | 27 Jun 2026 | 27 Jun 2027 | 1.29 | 13 Dec 2023 | 28 Dec 2024 |28 Feb 2025
4.15 | 27 Feb 2024 | 27 Sep 2024 | 27 Aug 2025 | N/A |N/A | 1.28 | 23 Aug 2023 | 28 Aug 2024 |28 Oct 2024
4.14 | 31 Oct 2023| 27 May 2024 | 1 May 2025 | 31 Oct 2025 | 31 Oct 2026 | 1.27 | 11 Apr 2023 | 14 Apr 2024 |28 Jun 2024
4.13 | 17 May 2023 | 31 Jan 2024 | 17 Nov 2024 | N/A |N/A |  1.26 | 9 Dec 2022 | 28 Dec 2023 | 28 Feb 2024
4.12 | 17 Jan 2023 | 17 Aug 2023 | 17 Jul 2024 | 17 Jan 2025 |N/A | 1.25 | 23 Aug 2022 | 8 Aug 2023 | 27 Oct 2023
4.11 | 10 Aug 2022 | 17 Apr 2023 |10 Feb 2024 |  N/A |N/A |1.24 | 3 May 2022 | 28 May 2023 | 28 Jul 2023
4.10 |10 Mar 2022| 10 Nov 2022 | 10 Sep 2023 |  N/A |N/A |1.23 | 7 Dec 2021 | 28 Dec 2022 | 28 Feb 2023
4.9 | 18 Oct 2021 | 10 Jun 2022 |18 Apr 2023|  N/A |N/A |1.22 | 4 Aug 2021 | 8 Aug 2022 | 28 Oct 2022
4.8 | 27 Jul 2021 | 27 Jan 2022 | 27 Jan 2023 | N/A |N/A | 1.21 | 8 Apr 2021 | - | 28 Jun 2022
4.7 | 24 Feb 2021| 27 Oct 2022 | 24 Aug 2022 | N/A |N/A |1.20 | 8 Dec 2020 | - |28 Feb 2022
4.6 EUS | 27 Oct 2020 | 24 Mar 2021 | 27 Oct 2022 |N/A |N/A |1.19 | 26 Aug 2020 | - |28 Oct 2021

Notes From kubernetes.io:
- The Kubernetes project maintains release branches for the most recent three minor releases (1.28, 1.27, 1.26). (Source: https://kubernetes.io/releases/)
- Kubernetes 1.19 and newer receive approximately 1 year of patch support. (Source: https://kubernetes.io/releases/patch-releases/#support-period)
- Since v1.22 was released in August 2021 Kubernetes makes new releases three times per year. (Source: https://kubernetes.io/blog/2021/07/20/new-kubernetes-release-cadence/)

### Appendix
- [Red Hat OpenShift Container Platform Life Cycle Policy](https://access.redhat.com/support/policy/updates/openshift)
- [What version of the Kubernetes API is included with each OpenShift 4.x release?](https://access.redhat.com/solutions/4870701)
- [Kuberenetes Release History](https://kubernetes.io/releases/#release-history) - Not a Red Hat web site
- [Kuberentes SIG Release Informaton](https://github.com/kubernetes/sig-release/tree/master/releases) - Not a Red Hat web site

