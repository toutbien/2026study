#Break Week Tasks

Build a small cluster and intentionally:

give a Service the wrong selector
point a pod at a bad image
break a readiness probe
give a PVC the wrong StorageClass
kill kubelet
apply an incorrect NetworkPolicy
create a scheduling constraint no node satisfies
mess up RBAC
break DNS resolution
roll out a bad deployment
make a node unschedulable

+ diagnose it from the CLI.
