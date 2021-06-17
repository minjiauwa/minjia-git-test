pipeline {
  agent any
  stages {
    stage('step1') {
      steps {
        echo 'mj0617_git01_test'
      }
    }

  }
  parameters {
    text(defaultValue: '1', description: '', name: 'm1')
    choice(choices: ["a", "b", "c", "def"], description: '', name: 'm2')
    text(defaultValue: '123456', description: 'password', name: 'm3')
    string(defaultValue: '4', description: '', name: 'm4', trim: false)
    booleanParam(defaultValue: true, description: '', name: 'm5')
  }
}