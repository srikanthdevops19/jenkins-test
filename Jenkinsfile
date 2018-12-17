node 
{
  stage "download"
checkout scm

stage "clean"
sh "cd my-app; mvn clean"

stage "test"
print "hello"
stage "deploy"
print "world"
stage "stage4"
print "world2"
stage "stage5"
print "welcome"
sh "cd my-app;mvn test"

stage 'pacakge'
sh "cd my-app;mvn package"
}

