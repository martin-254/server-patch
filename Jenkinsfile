pipeline {
   agent{
     lable 'ansible-server'
   }
  stages {
    stage ('deploy patch playbook') {
      steps {
        dir('/home/ec2-user/ansible-dev'){
          ssh ansible-playbook patch.yml'
        }
    }
  }
}
