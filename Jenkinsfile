def version = ''
def props = ''
def branchName = env.BRANCH_NAME.toLowerCase() //make lowercase because startsWith is case sensitive
def buildNum = ''
echo "Branch Name = ${branchName}"

node{

        cleanWs notFailBuild: true
	checkout scm
	props = readYaml file: 'project.yaml'
	
  
}
