def newGit(repo)
{ 
  git "${repo}"
}

def newMaven()
{
  sh 'mvn package'
}

def runSelenium(jobname)
{
  sh "java -jar /home/ubuntu/.jenkins/workspace/${jobname}/testing.jar"
}
