pipeline {
	agent any
    environment{
        NEW_VERSION = '1.0.0'
    }
	stages {
		stage("build") {
			steps {
				echo 'building the application...'
                echo "building version ${env.NEW_VERSION}"
			}
		}
		stage("test") {
			steps {
				echo 'testing the application...'
			}
		}
		stage("deploy") {
			steps {
				echo 'deploying the application...'
			}
		}
	}
}