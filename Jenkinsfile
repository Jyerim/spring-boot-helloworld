node{
	dir('spring-boot-helloworld'){
		stage('generate target folder'){
			sh './mvnw clean package'
		}
	}
	dir('spring-boot-helloworld/target'){
		stage('execute java'){
			sh 'java -jar *.jar'
		}
	}
}
