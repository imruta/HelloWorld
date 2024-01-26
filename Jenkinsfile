pipeline{
    agent any
    stages{
	stage('Compile code'){
	echo "Compiling the program....."
	sh 'javac HelloWorld.java'
             }
          }	
	stage(Run code){
        echo "Running the program....."
        sh 'java HelloWorld'
             }
          } 

}
