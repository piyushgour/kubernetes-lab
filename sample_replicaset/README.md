1. Add ROOT level Properties 
Ans- 
apiVersion: apps/v1
kind: ReplicaSet
metadata:
spec:

2. Update Metadata field 
Instruction: Name the ReplicaSet - frontend. And add labels app=>mywebsite and tier=> frontend

Ans- 
apiVersion: apps/v1
kind: ReplicaSet
metadata:
  name: frontend
  labels:
    app: mywebsite
    tier: frontend
spec:


3. Update "spec" section for ReplicaSet 
Ans- i.e. replica, templete, selector 

check sample_replicaset.yml for final result. 