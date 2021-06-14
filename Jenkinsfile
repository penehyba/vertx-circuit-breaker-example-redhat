node("launchpad-maven") {
  checkout scm
  stage("Build") {
    sh "mvn oc:deploy -Popenshift -DskipTests"
  }
  stage("Deploy")
}
