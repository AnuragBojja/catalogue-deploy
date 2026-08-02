@Library('jenkins-shared-lib') _

def configMap = [
    project: "roboshop",
    component: "catalogue"
]

if ( ! env.BRANCH_NAME.equalsIgnoreCase("main") ){
    EKSDeploy(configMap)
}
else {
    echo "need permision"
}