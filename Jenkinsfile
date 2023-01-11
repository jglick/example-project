podTemplate {
  node(POD_LABEL) {
    stage('prep') {
      checkout scm
    }
    stage('main') {
      sh 'ls && sleep 1m'
    }
  }
}
