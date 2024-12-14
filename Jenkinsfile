@Library('jekins-shared-library') _ // gets the global pipeline libraries in system configuration

def configMap = [
    project: "expense",
    component: "backend"
]


if ( ! env.BRANCH_NAME.equalsIgnoreCase('main')) {  // true if branch is feature branch
    
    nodejsEKSPipeline(configMap)
  
}
else {
    echo " please follow the process of prod release "
}