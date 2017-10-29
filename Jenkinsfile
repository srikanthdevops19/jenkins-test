stage "download"
checkout scm

stage "clean"
sh "mvn clean"

stage "test"
sh "mvn test"

stage 'pacakge'
sh "mvn package"
