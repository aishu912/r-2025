pipeline{
        agent any
  stages{
    steps("master"){
      stage{
          sh "systemctl restart httpd"
          sh "chmod -R 755 /var/www/html"
          echo "On master branch"
      }
    }
  }
}
