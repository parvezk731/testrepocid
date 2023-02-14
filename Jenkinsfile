node{
	stage('git coneection')
	{	
		git 'https://nddeo@bitbucket.org/nddeo/testrepocid.git'
		}
		stage('compile')
		{
			dev mvmHome = tool name: 'maven-3.9.0', type: 'maven'
			sh "${mvmhome}/bin/mvn package
			}
			}