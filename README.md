# hpe_csi_driver

  oc create secret generic vsphere-config-secret --from-file=csi-vsphere.conf --namespace=kube-system

  oc apply -f vsphere-csi-controller-rbac.yaml

  oc apply -f vsphere-csi-controller-ss.yaml

  oc apply -f vsphere-csi-node-ds.yaml

  oc get deployment --namespace=kube-system

  oc describe csidrivers

  oc get CSINode

  

