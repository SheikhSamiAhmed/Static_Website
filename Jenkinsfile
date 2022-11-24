pipeline {
    agent any
    stages {
        stage('Test on Windows') {
            steps {
                bat '''
                    git clone https://github.com/SheikhSamiAhmed/Static_Website.git;
                    dir
                    deploywebsite.bat
                '''
            }
        }
    }
}
