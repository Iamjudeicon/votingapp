node {

    stage('SCM Checkout')
    {
        git crendentialsid: 'c42dd7b2-07c2-4e82-89d7-b07ff252aa73', url: 'https://github.com/Iamjudeicon/votingapp.git'
    }
    stage ('Run Docker Compose File')
    {
        sh 'sudo docker-compose build'
        sh 'sudo docker-compose up -d'
    }
}
