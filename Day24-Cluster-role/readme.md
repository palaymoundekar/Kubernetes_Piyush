There are two tyepes of scope ;- 1. Namespace scope 2. cluster scope.

namespce scope       |  clutser scope
  * pods             |    * namespace
  * deployment       |    * nodes
  * rs, services     |


kubectl create clusterrole clutser-role --verb=list,get,watch  --resource=node


kubectl create clusterrolebinding clutser-binding-role --clusterrole=clutser-role --user=palay
