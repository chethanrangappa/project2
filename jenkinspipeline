pipeline{
    
    agent master 
    
    stages {
        stage ('BUILD'){
             sh   'ant war'
             
             sh ' cp dist/*.war /opt/apache-tomcat-8.5.24/webapps/'
            
            }
        
    }
}
