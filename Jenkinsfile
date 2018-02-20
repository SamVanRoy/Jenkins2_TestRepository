pipeline {
  agent any
  stages {
    stage('Mail 1') {
      steps {
        mail(subject: 'Test1', body: 'Dit is test1', from: 'saxo4sam@gmail.com', to: 'saxo4sam@gmail.com')
      }
    }
    stage('Mail 2') {
      steps {
        mail(subject: 'Test2', body: 'Dit is test2', from: 'saxo4sam@gmail.com', to: 'saxo4sam@gmail.com')
        mail(subject: 'MailExtra', body: 'Dit is een extra mail van mail2', from: 'saxo4sam@gmail.com', to: 'saxo4sam@gmail.com')
      }
    }
  }
}