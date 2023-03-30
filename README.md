# devops-essentials-sample-app

This is a simple sample application intended to be used alongside the labs for DevOps Essentials.

1. Create a pull request from the "new-feature" branch to "master" and merge it.
2. Run the Jenkins build and in the pipeline, confirm the change on production environment upon successful staging check.
3. Repeat steps 1 and 2 for "broken-feature" branch.
4. Roll back the broken deployment by Replaying the job with bug-free build. 
