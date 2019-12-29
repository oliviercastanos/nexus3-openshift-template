# nexus3-openshift-template

oc create -f nexus3-pvc.yaml
oc create -f nexus3-template.yaml
oc process nexus3 | oc create -f -
