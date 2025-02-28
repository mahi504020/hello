pipeline
{
agent any
  stages{
    stage("clone")
    {
      steps{
        git 'https://github.com/mahi504020/hello.git'
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
