pipeline {
  agent any
  stages {
    stage('Setup Docker') {
      steps {
        sh 'ansible-playbook --vault-pass-file=~/.ansible_pass setup-test.yml'
      }
    }
  }
}
