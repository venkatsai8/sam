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
		 branch 'test'
		}
		steps {
		echo " this is test stage"
	}
      }
	stage("Third") {
            when {
                 branch 'deploy'
                }
                steps {

                echo " this is deploy stage,hvhfjdbvfddjdj"

        }
      }
	stage("four") {
		steps{
		echo "final"
	}
      }
   }
}
