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
     }
}
