node('slave') 
{
  stage('Continuous Download') 
  {
    git branch: 'main', changelog: false, poll: false, url: 'https://github.com/jaiswaladi246/Shopping-Cart.git'
  } 
  stage('ContinuousBuild') 
  {
    sh 'echo "HELLO Ranganath"'
  } 
}
