Get started with javaFirst
-----------------------------------
Welcome to Java Web Starter application!

This sample application demonstrates how to write a Java Web application (powered by WebSphere Liberty) and deploy it on Bluemix.

1. [Install the cf command-line tool](https://www.ng.bluemix.net/docs/#starters/BuildingWeb.html#install_cf).
2. [Download the starter application package](https://ace.ng.bluemix.net:443/rest/../rest/apps/a16f52aa-4c8e-4c9c-83ff-a7a30fe15cc8/starter-download).
3. Extract the package and `cd` to it.
4. Connect to Bluemix:

		cf api https://api.ng.bluemix.net

5. Log into Bluemix:

		cf login -u jamieishere@live.cn
		cf target -o jamieishere@live.cn -s dev
				
6. Compile the Java code and generate the war package using ant.
7. Deploy your app:

		cf push javaFirst -p webStarterApp.war

8. Access your app: [http://jamiejavafirst.mybluemix.net](http://jamiejavafirst.mybluemix.net)
