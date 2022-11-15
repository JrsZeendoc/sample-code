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
        tpJobRun(projectId: 'yMc68Oy_7EisOGHp3ZCehQ-2fsVQ', jobId: 'qvu-uwwWHUeyJRoC48hQdQ', waitJobFinishSeconds: 300, junitResultsFile: 'reports/junit.xml')
      }
    }

    stage('report') {
      steps {
        echo 'report'
      }
    }

  }
}
