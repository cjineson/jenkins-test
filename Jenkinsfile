pipeline {
	agent any
	stages {
        stage ('build') {
            steps {	  
            sh 'echo "A one line step"'
            sh ''' 
            echo "A multiline step"
            pwd
            ls -al
            '''
            }
		}
	}
}