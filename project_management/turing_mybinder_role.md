# Turing mybinder.org Cluster Admin Role

This document outlines the minimal responsibilities and requirements for the technical administrator of the BinderHub deployment _The Turing Way_ donates to the [Binder Federation](https://blog.jupyter.org/the-international-binder-federation-4f6235c1537e).

---

## Context

_The Turing Way_ supports and maintains a Kubernetes cluster that is part of the Binder Federation, facilitating the decentralisation of the mybinder.org service.
This cluster also hosts Hub23, a private BinderHub for the Turing research community.
Maintaining this infrastructure requires technical skill and a small time commitment that are detailed below.

It is important to the Binder Operating team that we are not anonymous GitHub handles to one another.
Knowing who we are and why we're here helps us support each other and connect those who can help each other.
Please do say hi and [introduce yourself](https://discourse.jupyter.org/t/introduce-yourself/17)! :smile:

## Requirements

The person in this role must be a member of the Turing Institute with an `@turing.ac.uk` domain email.
This is due to the dependency on Turing internal processes/platforms, such as points 1 and 2 below.

1) An account in the Turing's Azure tenancy
2) Access to the `turingmybinder` subscription (can be arranged with IT Services through Top Desk)
3) Knowledge of Kubernetes and Helm

## Responsibilities

Deployments are managed by CI in the [mybinder.org-deploy repo](https://github.com/jupyterhub/mybinder.org-deploy) and so day-to-day tasks are minimal and relatively non-disruptive.

- Watch the [team-compass](https://github.com/jupyterhub/team-compass) for any relevant updates or opportunities for participation
- Attend the [monthly team meetings](https://jupyterhub-team-compass.readthedocs.io/en/latest/meetings.html) when able.
  The link above contains a monthly report archive to catch up on missed meetings.
- Be available in the [mybinder.org-deploy gitter chat](https://gitter.im/jupyterhub/mybinder.org-deploy) to liaise with the operating team should the cluster experience any technical difficulties
- Be willing to co-work/pair programme with the mybinder.org operating teams to debug any issues with the cluster.
  Particularly [Tim Head](https://github.com/betatim) who is the only other person with direct access to the subscription.
- Monitor the `turingmybinder` subscription credits on Azure (under the Turing's tenancy) and [file requests for additional credits](https://turingcomplete.topdesk.net/tas/public/ssp/content/serviceflow?unid=fabf0809069f42a5a36c61d677da08fa&openedFromService=true) using [the template](credit_requests/turing_mybinder_azure_credit_request_template.md).
  Credit requests are made to the Turing's Microsoft Sponsorship fund so there shouldn't be a time limit on funding, but of course this is constrained by Microsoft's continuation of the Sponsorship.
  - The candidate may also be required to fill in surveys on Turing's Azure usage to feedback to Microsoft.
    The Binder Federation Cluster has been showcased in Azure reports previously.
  - **N.B.:** Now that Hub23 and the Turing Federation Hub share the same infrastructure/subscription, this template and further credit requests may need updating.
    For example, there are now 2 key vaults and 2 DNS zones deployed in the subscription, alongside 1 Kubernetes cluster and 1 Azure Container Registry.
- Merge Pull Requests from [HelmUpgradeBot](https://github.com/HelmUpgradeBot) on the [hub23-deploy repo](https://github.com/alan-turing-institute/hub23-deploy).
  These PRs keep the Hub23 deployment up-to-date with helm chart releases from BinderHub and `ingress-nginx`.
  - It is up to the person in the role if they would like to continue the development of Hub23, however, this is beyond the scope of "minimal" responsibilities.
    [@sgibson91](https://github.com/sgibson91) is happy to discuss further with any interested parties.

## Recommended Tools

Beyond the CLIs for [Azure](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli), [Kubernetes](https://kubernetes.io/docs/tasks/tools/) and [Helm](https://helm.sh/docs/intro/install/), the following tools can make managing a Kubernetes deployment easier:

- [Lens](https://k8slens.dev/): an IDE for Kubernetes deployments
- [`kubectx` and `kubens`](https://github.com/ahmetb/kubectx): quickly change Kubernetes contexts and namespaces
- [`stern`](https://github.com/wercker/stern): concatenate logs from multiple pods/services/etc ([See blog](https://kubernetes.io/blog/2016/10/tail-kubernetes-with-stern/))

## Useful Resources

- [mybinder.org Site Reliability Guide](https://mybinder-sre.readthedocs.io)
- [Hub23 Deployment Guide](https://alan-turing-institute.github.io/hub23-deploy)