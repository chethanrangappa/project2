pipeline{
    
    agent Master
    
    stages {
        stage ('BUILD'){

	steps {
             sh   'ant'
             
             sh ' cp -Rp /root/.jenkins/workspace/firstpip/dist/AntExample.war  /opt/apache-tomcat-8.5.24/webapps/'
            
            }
        }
    }
}
