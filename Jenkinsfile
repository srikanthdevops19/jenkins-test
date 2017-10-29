node 
{
  stage "download"
checkout scm

stage "clean"
sh "cd my-app; mvn clean"

stage "test"
sh "cd my-app;mvn test"

stage 'pacakge'
sh "cd my-app;mvn package"
}
