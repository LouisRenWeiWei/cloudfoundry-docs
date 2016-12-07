##Overview of Deploying Cloud Foundry

Cloud Foundry is designed to be configured, deployed, managed, scaled, and upgraded on any cloud IaaS provider. Cloud Foundry achieves this by leveraging [BOSH], an open source tool for release engineering, deployment, lifecycle management, and distributed systems monitoring.

At a high level, the steps are the same regardless of IaaS:

1. Set up all external dependencies, such as IaaS account, external load balancers, DNS records, and any additional components.
2. Create a manifest to deploy a BOSH Director.
3. Deploy the BOSH Director.
4. Create a manifest to deploy Cloud Foundry.
5. Deploy Cloud Foundry.

We also offer a quick `vagrant up` solution for steps 1-3 to let you focus on pushing apps or hacking on Cloud Foundry itself.

Select one of the core supported infrastructures below to get started:

* AWS
* OpenStack
* vSphere
* vCloud Air or vCloud Director
  Or, if you just want the `vagrant up` experience, use BOSH-Lite:
* BOSH-Lite
