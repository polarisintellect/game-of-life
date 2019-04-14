node {
    stage('scm') {
    // some block
    git 'https://github.com/wakaleo/game-of-life.git'
}
 stage('buildpackage') {
    // some block
    sh label: '', script: 'mvn package'
}
 stage('archive') {
    // some block
    archive 'gameoflife-web/target/*.war'
}
 
}
