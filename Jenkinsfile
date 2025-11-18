@Library('jenkins-shared-library') _

def configMap = [
    project : "sample",
    component : "brocklesner"
]

if(env.BRANCH_NAME.equalsIgnoreCase("main")){
    samplePipeline(configMap)
}
else{
    echo "Please proceed with Prod"
}
