pipeline{
        agent{
                label{
                        label 'built-in'  // Optional, specify a label if needed
                        customWorkspace '/var/www/html'        
                }
        }
  stages{
    stage('master'){
      steps{
          sh "systemctl restart httpd"
          sh "chmod -R 755 /var/www/html"
          echo "From 2025Q3 branch"
      }
    }
  }
}
