1. You can use this command to get all the credentials that are used in this script: az ad sp create-for-rbac --name "myML" --role contributor --scopes /subscriptions//resourceGroups/ --json-auth

2. and set all secrets in our repo secret, and run the job.
