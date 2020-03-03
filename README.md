# openshift-4-3

Working on a installation of Red Hat OpenShift Container Platform 4.3 (OCP) on VMware vSphere using the following sample document https://labs.consol.de/container/platform/openshift/2020/01/31/ocp43-installation-vmware.html

## Basic BIGIP LB setup
This configuration will add the following load balancer entries to the F5 BIGIP using AS3:

* openshift-api-server (port 6443)
* machine-config-server (port 22623)

BIGIP OpenShift API configuration [example](https://github.com/mdditt2000/openshift-4-3/blob/master/lb-ocp4-3-api.json)




