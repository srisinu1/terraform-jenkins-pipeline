pipeline{
  agent any
    stages
  {
    stage("clone repo"){
      steps
      {
        git branch: 'main', url: 'https://github.com/srisinu1/terraform-jenkins-pipeline.git'
      }
    }
stage('terraform init') {
steps {
  sh 'terraform init'
     }
}
stage('terraform validate') {
steps {
  sh 'terraform validate'
     }
}
stage('terraform plan') {
steps {
  sh 'terraform plan'
     }
}
 stage('terraform apply') {
steps {
  sh 'terraform apply'
     }
    }
  }
