# casc

Install the ```configuration-as-code``` plugin

Export the config  ```<coreurl>/core-casc-export```

Create the files, edit specific information from the file including oc connection config

Create a freestyle job, use git plugin and set user name and password creds, using
dev token as the password, use https

freestype job ```cp -r m1 $JENKINS_HOME/jcasc-bundles-store```