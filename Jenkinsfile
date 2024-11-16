pipeline{
        agent any
  stages{
    stage("master"){
      step{
          sh "systemctl restart httpd"
          sh "chmod -R 755 /var/www/html"
          echo "On master branch"
      }
    }
  }
}
