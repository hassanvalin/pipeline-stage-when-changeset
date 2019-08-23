pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when{
				changeset glob: "WORLD.js" casesensitive: true
			}
		
            steps {                
                echo 'Hello World changeset JS'
            }
        }
    }
}
