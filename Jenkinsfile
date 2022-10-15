pipeline{
  agent any
  stages{
    stage('Restore packages') {
      steps {
        bat "dotnet restore ${my-pipeline_master}\\JenkinsDotNetDemo.sln"
      }
    }
  }
}
