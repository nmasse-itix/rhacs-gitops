# Deploy Red Hat ACS, the GitOps way!

An all-in-one installation of [Red Hat ACS](https://docs.openshift.com/acs/4.3/welcome/index.html) using GitOps:

- Red Hat ACS Operator
- **Central** installation
- [Init bundle](https://docs.openshift.com/acs/4.3/installing/installing_ocp/init-bundle-ocp.html) generation
- **Secure Cluster Service** installation
- Dedicated route for the console with the default router certificate. That is to say, no more "invalid certificate" warning!
- Post-configuration hook to deploy Red Hat ACS configuration
- A link to the Central from within the OpenShift Console
