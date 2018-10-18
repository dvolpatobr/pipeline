node {
    checkout scm

    def customImage = docker.build("fisclusteruat.icp:8500/default/testeimg:${env.BUILD_ID}")

    customImage.inside {
        sh 'echo "ok"'
    }
}