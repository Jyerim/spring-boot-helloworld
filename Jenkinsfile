node {
   
    stage('generate target folder') {
         sh 'chmod u+x mvnw'
	 sh './mvnw clean package'
    }
    
    dir('target'){
        stage('execute java') {
        	sh 'java -jar *.jar'
	}
    }

}
