This is a workable php7 apache container that can work with VSCODE. 

Try it free. 

The launch.json of the workspace is actually in .vscode folder and you can delete it to replace another one if you want to configure by yourself.


You probably need to add this line in the /etc/hosts of docker host:

172.17.0.1 host.docker.internal

you can use local vscode to debug php or you can use vscode in windows and connect to host by remote SSH. everything is the same.



