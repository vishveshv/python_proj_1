@Library('python_compile') _
pipeline
{
  agent any
  stages
  {
   stage('build')
   {
    steps
     {
       sh(libraryResource('com/nvidia/python.sh'))
     }
   }
  }
}
