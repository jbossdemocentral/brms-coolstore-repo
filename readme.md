JBoss BRMS Cool Store Demo
==========================

Install the application into JBoss BRMS
---------------------------------------

Note: JBoss BRMS (can be downloaded from https://access.redhat.com/) is already installed.

Before starting the installation add the loanOfficer role to the user which is used to login in Business Central.

1. Open the Business Central (ex. http://<your_ip>:<port>/business-central)
2. Login (u:erics / p:bpmsuite)
3. From the main meniu select `Authoring -> Administration`
4. From the secondary menu select `Repositories -> Clone repository`
5. Fill the Clone Repository form:
  - Repository Name - the name of the repository (created inside JBoss BPM Suite)
  - Organizational Unit - select a value from list
  - Git URL - https://github.com/jbossdemocentral/brms-coolstore-repo.git 
  - Leave User Name and Password fields empty

