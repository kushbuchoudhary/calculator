pipeline{
  agent any
  stages{
    stage('clone'){
      steps{
        git branch:'main',url:'https://github.com/kushbuchoudhary/Calculator.java'
          ]
      }
      stage('compile'){
        steps{
          sh'javac Calculator.java'
        }
      }
      stage('build'){
        steps{
          sh'java Calculator 25 5'}
      }
    }
  }
  
