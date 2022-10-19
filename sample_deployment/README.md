Deployment are same as ReplicaSet but its change "Kind".
Deployment create new Object.


1. Add Core values of "Deployment".

Instruction: Update values for apiVersion and kind


2. Add Metadata field.

Instruction: Name the Deployment frontend. And add labels app=>mywebsite and tier=> frontend


3. Add "Replica", "Selector" and "Template" for final configration.

Solution - Check sample_deployment.yml file.

