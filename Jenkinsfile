pipeline {
    agent any
    stages {
        stage("First") {
            when {
                branch 'nat'
            }
            steps {
                echo "Hello World!"
                echo "This is branch nat"
            }
        }
	stage("Second") {
            when {
                branch 'dev'
            }
            steps {
                echo "This is branch Developer"
            }
        }
	stage("Third") {
            when {
                branch 'test'
            }
            steps {
                 echo "This is branch Test"
            }
        }
	stage("FInal") {
	   when {
		branch 'master'
          }
	  steps{
		echo "This is the main branch"
		echo "new one maaa"
	 }
        }
     }
}
