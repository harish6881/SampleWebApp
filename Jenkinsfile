node{
    stage{'SCM Checkout'){
    git 'https://github.com/harish6881/SampleWebApp'
    }
    stage('Compile-Package'){
    def mvnHOME = tool name: 'maven-3',type: 'maven'
    sh "${mvnHOME}/bin/mvn" package 
    }
    
   }
