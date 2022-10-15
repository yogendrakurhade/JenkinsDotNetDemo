pipeline{
  agent any
  stages{
    stage('Restore packages') {
      steps {
        bat "dotnet restore $${workspace}\\{my-pipeline_master}\\JenkinsDotNetDemo.sln"
      }
    }
  }
}
