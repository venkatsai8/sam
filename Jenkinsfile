pipeline {
    agent {}
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
   }
}
