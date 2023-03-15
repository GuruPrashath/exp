pipeline {
  agent any  

    stages{
    stage('SonarCodeAnalysis') {
            steps {	
		sh 'mvn clean verify sonar:sonar -Dsonar.projectKey=hamritha02 -Dsonar.organization=hamritha02 -Dsonar.host.url=https://sonarcloud.io -Dsonar.login=0b21a239198f368ba422627dc797d73564383739'
			}
       }
   }
}
