pipeline{
agent any
 Steps{
  stage('Build'){
step{
   echo 'Running build automation'
   sh'./gradle build --no-demon'
   archiveArtifacts:'dist/trainSchedule.zip'
}
}
}
}
