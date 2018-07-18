node {

    checkout scm

    stage "Deploy to infrastructure"

    	sh "kubectl apply --recursive -f apps/"
}
