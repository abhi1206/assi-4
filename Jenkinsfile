pipeline{
    agent{
         label{
           label 'built-in'
}
}
    stages{
      stage('deploy GOL'){
        steps{
          sh"cp -r /mnt/project/game-of-life/gameoflife-web/target/gameoflife.war /mnt/server/apache-tomcat-9.0.68/webapps"
          sh"chmod -R 777 /mnt/server/apache-tomcat-9.0.68/webapps/gameoflife.war"
}
}
}
}
