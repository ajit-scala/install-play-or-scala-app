# install-play-or-scala-app
How to install play app as daemon or any other scala app 

* https://www.playframework.com/documentation/2.5.x/Deploying
* :Transformation
Actually there is only 1 application.conf per project. In short - in application.conf you place default configuration of your app, and additionally you need to create additional files for you environment(s) ie. life.conf, dev.conf etc. In these files you first need to include application.conf (which will read whole default configuration) and next just overwrite only parts which have to be changed - ie. DB credentials, it could be dev.conf:
https://www.playframework.com/documentation/2.5.x/ProductionConfiguration
* http://stackoverflow.com/questions/21865407/play-framework-how-to-maintain-configuration-files-for-different-environments
