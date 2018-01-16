pipeline{
    
    agent master 
    
    stages {
        stage ('BUILD'){

	steps {
             sh   'ant war'
             
             sh ' cp dist/*.war /opt/apache-tomcat-8.5.24/webapps/'
            
            }
        }
    }
}
