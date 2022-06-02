node('master') 
{
    stage('Continuous Download_deposits') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_deposits') 
	{
    sh label: '', script: 'mvn package'
	}
}
