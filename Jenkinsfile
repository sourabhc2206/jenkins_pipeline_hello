node {
    stage('build'){
        echo "building"
    }
}
node {
    stage('test'){
        echo "testing"
    }
}
stage('Get approval'){
    input "Deploy to qa?"
}
node {
    stage('deploy to qa'){
        echo "deploying"
    }
}
node { 
    stage (' deploy to UAT') {
        echo "deploy to UAT" 
    }
    }
node {
    stage (' deploy to devint2') {
        echo "deploooooyyyyyy" 
    }
}
