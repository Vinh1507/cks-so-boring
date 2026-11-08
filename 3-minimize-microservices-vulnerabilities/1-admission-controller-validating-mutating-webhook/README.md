We know that in Kubernetes StatefulSets, we can only specify one StorageClass for all pods managed by a StatefulSet. However, in some cases, we need a database (which is typically deployed as a StatefulSet) to have pods using different StorageClasses, potentially across multiple regions.

--> https://github.com/Vinh1507/multi-storage-class-k8s