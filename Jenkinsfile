node {
    withCredentials([usernamePassword(credentialsId: 'artifactory', usernameVariable: 'ARTIFACTORY_USR', passwordVariable: 'ARTIFACTORY_PSW')]) {
        echo 'Hello world'
        echo $ARTIFACTORY_USR
        echo $ARTIFACTORY_PSW
    }
}
