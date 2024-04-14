node {

    stage('checkoutcode') 
    { 
        git credentialsId: '9ca6af50-61dc-4cf0-b2c6-21643821f4ab', url: 'https://github.com/nithusolutions/webapp.git'
    }
    stage('Build') {
        // Run the maven build
       bat "mvn clean package"
    }
   
}

