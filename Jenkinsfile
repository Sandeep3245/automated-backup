pipeline {
    agent any
    stages {
        stage('Backup') {
            steps {
                bat '"C:\\Program Files\\Git\\bits\\bash.exe" -c "chmod +x backup.sh && ./backup.sh"'
            }
        }
    }
}