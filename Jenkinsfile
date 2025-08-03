pipeline {
    agent any

    stages {
        stage('A') {
            steps {
                echo 'Stage A'
                bat 'ping -n 6 127.0.0.1 > nul'
                bat 'powershell Start-Sleep -Seconds 5'
                // timeout often fails in Jenkins, use cautiously
                bat 'echo Y | timeout /t 5 /nobreak'
            }
        }
        stage('B') {
            steps {
                echo 'Stage B'
                bat 'ping -n 6 127.0.0.1 > nul'
                bat 'powershell Start-Sleep -Seconds 5'
                bat 'echo Y | timeout /t 5 /nobreak'
            }
        }
        stage('C') {
            steps {
                echo 'Stage C'
                bat 'ping -n 6 127.0.0.1 > nul'
                bat 'powershell Start-Sleep -Seconds 5'
                bat 'echo Y | timeout /t 5 /nobreak'
            }
        }
        stage('D') {
            steps {
                echo 'Stage D'
                bat 'ping -n 6 127.0.0.1 > nul'
                bat 'powershell Start-Sleep -Seconds 5'
                bat 'echo Y | timeout /t 5 /nobreak'
            }
        }
        stage('E') {
            steps {
                echo 'Stage E'
                bat 'ping -n 6 127.0.0.1 > nul'
                bat 'powershell Start-Sleep -Seconds 5'
                bat 'echo Y | timeout /t 5 /nobreak'
            }
        }
        stage('F') {
            steps {
                echo 'Stage F'
                bat 'ping -n 6 127.0.0.1 > nul'
                bat 'powershell Start-Sleep -Seconds 5'
                bat 'echo Y | timeout /t 5 /nobreak'
            }
        }
        stage('G') {
            steps {
                echo 'Stage G'
                bat 'ping -n 6 127.0.0.1 > nul'
                bat 'powershell Start-Sleep -Seconds 5'
                bat 'echo Y | timeout /t 5 /nobreak'
            }
        }
        stage('H') {
            steps {
                echo 'Stage H'
                bat 'ping -n 6 127.0.0.1 > nul'
                bat 'powershell Start-Sleep -Seconds 5'
                bat 'echo Y | timeout /t 5 /nobreak'
            }
        }
        stage('I') {
            steps {
                echo 'Stage I'
                bat 'ping -n 6 127.0.0.1 > nul'
                bat 'powershell Start-Sleep -Seconds 5'
                bat 'echo Y | timeout /t 5 /nobreak'
            }
        }
        stage('J') {
            steps {
                echo 'Stage J'
                bat 'ping -n 6 127.0.0.1 > nul'
                bat 'powershell Start-Sleep -Seconds 5'
                bat 'echo Y | timeout /t 5 /nobreak'
            }
        }
    }
}
