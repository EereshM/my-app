node {
    stage('SCM Checkout'){
      git 'https://github.com/EereshM/my-app.git'
    }
    stage ('Compile-Package'){
      sh 'mvn clean package'
     }
 }
