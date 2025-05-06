node('built-in'){
    stage('continuousDownlaod_master') {
     git 'https://github.com/gopiseshu/maven.git'
}
stage('continuousBuild_master') {
    sh '''mvn package
    '''
}
}
