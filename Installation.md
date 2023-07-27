oc login

oc logout

oc login -u cluster-address

oc project - what project we are currently using

oc new-project testproject - creates a project and sets it

oc project testproject - switch to the project

oc explain pod - gives the type of the object

oc explain pod.spec

oc explain pod.spec.containers

oc status - checks the status of the cluster

oc rsh podname - exec into the pod

oc delete pod podname

oc get pods --watch

