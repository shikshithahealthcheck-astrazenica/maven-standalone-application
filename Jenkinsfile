node 
{
    def mavenHome=tool name: "Maven3.6.3"
    stage('checkout')
    {
      git credentialsId: '4970c762-b912-402f-ac68-f5877a416d28', url: 'https://github.com/shikshithahealthcheck-astrazenica/maven-web-application.git'
    }
    /*
    stage('build')
    {
    sh "${mavenHome}/bin/mvn clean package"
    }
    stage('SonarReport')
    {
    sh "${mavenHome}/bin/mvn sonar:sonar"
    }
    stage('Artifact')
    {
     sh "${mavenHome}/bin/mvn deploy"
    }
    stage('DeployApptoTomcat')
    {
        sshagent(['3efdfdd8-54a3-49c4-8eae-d6c787b55640'])
        {
      sh "scp -o StrictHostKeyChecking=no target/maven-web-application.war ec2-user@3.15.173.65:/opt/apache-tomcat-9.0.43/webapps"
            
        }
    }
    stage('Send Email notification')
    {
        emailext body: '''Build is over
Thanks 
Shikshitha''', subject: 'Build is over', to: 'shikshithagowda76@gmail.com'
    }
    */
}

