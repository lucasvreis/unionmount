pipeline {
    agent {
        label 'nixos'
    }
    stages {
        stage ('Build') {
            steps {
                nixCI ()
            }
        }
    }
}
