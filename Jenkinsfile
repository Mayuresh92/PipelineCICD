pipeline{
    
    agent any
    stages{
        
        stage('Compile stage'){
            
            steps{
            
            bat 'mvn install'
            }

            }
        
        stage('Deploy stage'){
            
            steps{
                
                bat '''copy C:\\Users\\Mayuresh.Marathe\\.m2\\repository\\com\\example\\spring-pipeline-demo\\0.0.1-SNAPSHOT\\*.war C:\\Users\\Mayuresh.Marathe\\Desktop\\apache-tomcat-8.5.54\\webapps'''
            }
        }

        }

    

}
