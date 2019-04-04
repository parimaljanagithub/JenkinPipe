pipeline {
  agent any
  parameters {
        string(name: 'BRANCH_NAME', defaultValue: 'develop', description: 'The git branch or tag name')
        booleanParam(name: 'BUILD_FROM_TAG', defaultValue: false, description: 'Is this deployment build from a git tag?')
        booleanParam(name: 'IS_HOTFIX', defaultValue: false, description: 'Is this deployment for a hotfix?')
        booleanParam(name: 'INCR_MAJOR_VERSION', defaultValue: false, description: 'Are you going to increasing major version? (e.g. 2.x.0).')
        booleanParam(name: 'NEVER_TO_PROD', defaultValue: false, description: 'Will this deployment never go for PROD?')
        choice(name: 'REPO_TYPE', choices: 'SNAPSHOT\nRELEASE', description: 'Repository type (usually use SNAPSHOT)')
    }
        
 stages {
        stage('Stage_one') {
                          steps {
                                 echo 'inside stage one and step one'
                                }                                                       
                           }
        stage('stage_two') {
                          steps {
                                echo 'inside stage two and step 1'
                                 }
                             }

     }
}




