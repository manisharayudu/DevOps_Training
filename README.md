In this project I learnt how to trigger any changes on the the github repositories that will build the test on the Jenkins. For that I have taken a project of mine in the git repository and added the webhooks.

For this project I had run jenkins from the docker hub on the port of 8080 by using following command:

docker run -d -p 8080:8080 --name my jenkins jenkins/jenkins:latest

Once the container is running, then go on the server and create a job

New item > create a job > Freestyle project > ok

Source code Management > Git > URL of the git project

Under the git.. create git credentials.

Build triggers > Github hook trigger for Gitscm polling .

Once everything is done in the jenkins then go into the git hub. Open the project under setting> webhooks > payload url of jenkins > Add webhook.

That’s it, when any changes commited on the github then automatically a build will be generated on Jenkins.
