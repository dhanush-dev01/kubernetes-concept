this application covers kubernetes concepts of 
=>sql deployment 
=>persistent volumne claim 
=>storage class
=>kuberenetes secrets
=>nginx ingress 
=>services for pod 
=>namespace

Docker concepts of 
=>building custom image for reactjs and nodejs

CI/CD in Azure pipeline
=>build pipeline 
=>release pipeline 
=>based on the commit the pipeline will be trigged 

nodejs and express for backend 
=>understanding on api calls

reactjs 
=>building connections for backend

steps to be followed 

=> first deploy sql in in the cluster 
    
    * in the folder given deploy storage class , PVC and secrets before deploying sql yaml file 

=> if you want to test the code NodeJS and ReactJS locally you need to create load balancer for accessing 
    sql through workbench
    ***note: as it is not recommand to use loadbalacer in the release at last dont forget to change the service to clusterip for sql***

=> pull the code in ur azure repo and start with the pipeline 
    
