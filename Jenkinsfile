pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        
        stage('Print File Content') {
            steps {
                script {
                    def fileContent = readFile 'first file.txt'
                    echo "Content of the file:\n${fileContent}"
                }
            }
        }
    }
}
