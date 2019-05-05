node {
    stage('build'){
        echo "building"
    }
}
node {
    stage('test'){
        echo "testing starts"
    }
}
node {
    stage('preprod'){
        echo "move to preprod"
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
