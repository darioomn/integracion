#Docker Jenkins Guide

To use [Docker](https://www.docker.com/) to start [Jenkins](https://jenkins-ci.org/):

```
docker run -p 8080:8080 -p 50000:50000 jenkins
```

To [ssh](https://docs.docker.com/machine/reference/ssh/#ssh) into a [Docker Machine](https://docs.docker.com/machine/) (your linux virtual machine):

```
docker-machine ssh machinename
```

###Basic Docker Commands
`docker-machine start machine` Starts a stopped machine

`docker-machine stop machine` Stops machine

[more](https://docs.docker.com/engine/installation/mac/#learn-the-key-concepts-before-installing)

###Troubleshooting
Error Message: "Cannot connect to the Docker daemon. Is the docker daemon running on this host?"

Solution: `eval $(docker-machine env machinename)` to connect to Docker daemon(Docker Engine)

###References

[Docker on Mac OS X](https://docs.docker.com/engine/installation/mac/#learn-the-key-concepts-before-installing)

[Docker Jenkins](https://hub.docker.com/_/jenkins/)

[Docker CI Resources](http://www.docker.com/use-cases/continuous-integration#resources)

[Docker Self Pace Training](https://training.docker.com/self-paced-training)

[Docker Get Started](https://docs.docker.com/mac/)

[Docker Quick Start](https://docs.docker.com/engine/quickstart/#quickstart-docker-enginez)

#MarkDown CheatSheet
#h1
##h2
###h3
####h4
#####h5
######h6

_italicize_

**bold**

`inline code snippet`
```
multi-line
   code snippet
   with indentation
   ```
   
 ```javascript
var code = "javascript";
```  

 ```java
String code = "java";
```
1. [Stack Overflow][1] (number reference)
2. [Stack Overflow][so] (tagged reference)
3. [Stack Overflow](http://stackoverflow.com) (direct reference)

[1]: http://stackoverflow.com
[so]: http://stackoverflow.com







