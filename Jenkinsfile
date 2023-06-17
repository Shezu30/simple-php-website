pipeline{
    agent any
    environment{
        staging_server="13.232.159.128"
    }
    stages{
        stage('Deploy to Remote'){
            steps{
                sh 'scp -r ${WORKSPACE}${fil} ubuntu@${staging_server}:/var/www/html/mbaquatech${fil}'
                    
                        
                        
                    
                
            }
        }
    }
}
