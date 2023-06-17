pipeline {  
    agent any  
        stages {  
       	    stage("git_checkout") {  
           	    steps {  
              	    echo "cloning repository" 
              	    git branch: 'J2EE', url: 'https://github.com/ujjawalgami/onlinebookstore.git'  
              	    }
                steps {
                    echo "Maven Testing"
                    bat 'mvn clean test'
         	    } 
        }
}
