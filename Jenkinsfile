@Library('test-library') _

def configMap = [
    project = "Roboshop" ,
    component = "catalogue"
]

echo " Triggering multi branch pipeline"

if ( env.BRANCH_NAME.equalsIgnoreCase('main') ) {
    echo "will do it later"
}
else {
    testPipeline(configMap)
}