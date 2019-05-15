pipeline {
   post {
    always {
        mail to: 'ritortoalvaro93@gmail.com',
             subject: "Failed Pipeline: ${currentBuild.fullDisplayName}",
             body: "Something is wrong with ${env.BUILD_URL}"
         }
    }
}
