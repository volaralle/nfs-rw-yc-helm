helm install nfs-server stable/nfs-server-provisioner --set persistence.enabled=true,persistence.size=200Gi,storageClass.name=nfs
