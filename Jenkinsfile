pipeline 
{
agent { 
label 'newone'
}
stages {
  stage  ('checkout')
 {
 steps { 
         checkout scm
   }
 } 
  stage ( 'Build')
 {
 steps { 
         sh " cd /home/ec2-user/git/jenkins-pipeline-examples ; mvn clean install "

}
}
}
}
