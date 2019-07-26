node {
   
    stage('generate target folder') {
        sh './mvnw clean package'
    }
    
    dir('target'){
        stage('execute java') {
        sh 'java -jar *.jar'
    }

}
