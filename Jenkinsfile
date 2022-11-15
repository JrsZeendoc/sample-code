pipeline {
  agent any
  stages {
    stage('prepare') {
      steps {
        echo 'prepare-step'
      }
    }

    stage('run-test-job') {
      steps {
        tpJobRun(projectId: 'CLMgcB7Sr0CoW2Vm-2fsVQ', jobId: '9cf5yOumDUS7FSGsa36Bmw', agentId: 'S_Zcsb3S6EOgWD-rvpaJ5Q', waitJobFinishSeconds: 300, junitResultsFile: 'reports/junit.xml')
      }
    }

    stage('report') {
      steps {
        echo 'report'
      }
    }

  }
}