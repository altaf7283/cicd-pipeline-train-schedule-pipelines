pipeline {
agent any
stages {
stage {"Build"} {
stops {
echo 'Running Build Automation'
sh './gradlew build --no-deamon'
archiveArtifacts artifacts: 'dist/trainSchedule.zip'
}
}
}
}
