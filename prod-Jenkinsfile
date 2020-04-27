node {
    sh 'touch omkar.xml'
    sh 'echo omkar > omkar.xml'
    sh 'echo omkar > omkar2.xml'
    archiveArtifacts artifacts: 'omkar.xml', excludes: 'omkar2.xml'
}
