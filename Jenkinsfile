pipeline
{
agent any
  stages{
    stage("clone")
    {
      steps{
        git 
      }}
    stage("build")
          {
            steps{
              cmd  'javac Welcome.java'
            }
          }
          stage("run")
          {
            steps{
              cmd 'java Welcome'
            }
          }
          }
          }
