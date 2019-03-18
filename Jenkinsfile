node {
    
    docker.image('node:4.1.2').inside () {
         print "inside a node server"
         sh("echo test");
     }
    
    //checkout scm

    //def customImage = docker.build("fisclusteruat.icp:8500/default/testeimg:${env.BUILD_ID}")

 //   customImage.inside {
 //       sh 'echo "ok"'
 //       sh 'node --version'
 //   }
}
