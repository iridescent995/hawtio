# hawtio

how to run Hawtio:

1. add java agent in run configuration > vm args: -javaagent:D:\agents\Jolokia_agent\jolokia-1.6.0-bin\jolokia-1.6.0\agents\jolokia-jvm.jar=host=localhost,port=8090

2. run the project.

3. run hawtion. jar by running:  java -jar hawtio-app-2.4.0.jar --port 8070

4. it will open a console then connect it with jolokia

5. properties: localhost   port: 8090  path: jolokia 

6. hit connect
