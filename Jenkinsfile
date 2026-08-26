pipeline {
        agent any
        stages {
          stage('Checkout') {
        steps {git branch: 'main', credentialsId: 'd2734542-e938-4110-990d-cd05250eedc2', url: 'https://github.com/zeezaayy/repo-git.git'}
        }
          stage('Stage1') {
                steps {sh 'touch jenkins.txt'}
}
                
          stage('Stage2') {
                steps {sh 'touch jenkins2.txt'}
          }
                
        stage('Stage3') {
        steps {sh 'touch jenkins3.txt'}
        }
        }
}
