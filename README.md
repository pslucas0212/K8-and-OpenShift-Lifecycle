# Kubernetes and OpenShift Lifecycle

This documents compares the Kubernetes version release and support cycle with that of OpenShift's release and support cycle.  Last update 16 May 2022.  Check official documentaton (see Appendix below) to confirm correct dates before planning any activities.

### OCP Lifceycle Compared to K8 Lifecycle


OCP Version | OCP Release | OCP EOM | K8 Version | K8 Release | K8 EOL
------------|-------------|---------|------------|------------|-------
4.x | TBD | TBD | 1.25 | 08/23/2022 | TBD
4.x | TBD | TBD | 1.24 | 05/03/2022 |9/29/2023
4.10 | 03/10/2022 | 09/10/2023 | 1.23 | 12/07/2021 | 02/28/2023
4.9 | 10/18/2021 | 04/18/2021 | 1.22 | 08/04/2021 | 10/28/2022
4.8 | 07/27/2021 | 01/27/2023 | 1.21 | 04/08/2021 | 06/28/2021
4.7 | 02/24/2021 | 08/24/2022 | 1.20 | 12/08/2020 | 02/28/2022
4.6 EUS | 10/27/2020 | 10/27/2022 | 1.19 | xxx | xxx

Notes From kubernetes.io:
- The Kubernetes project maintains release branches for the most recent three minor releases (1.24, 1.23, 1.22). Kubernetes 1.19 and newer receive approximately 1 year of patch support.
- Kubernetes releases currently happen approximately four times per year. Paul comment: Reviewing the information at kubernetes.io, it looks like the project may be shifting to three release per year.

### Appendix
- [Red Hat OpenShift Container Platform Life Cycle Policy](https://access.redhat.com/support/policy/updates/openshift)
- [What version of the Kubernetes API is included with each OpenShift 4.x release?](https://access.redhat.com/solutions/4870701)
- [Kuberenetes Release History](https://kubernetes.io/releases/#release-history) - Not a Red Hat web site
- [Kuberentes SIG Release Informaton](https://github.com/kubernetes/sig-release/tree/master/releases) - Not a Red Hat web site

