@Library("shared_lib") _
pipeline{
    agent any
    parameters {
         string defaultValue: 'shubhambadade007', description: 'git user name', name: 'git_username'  
    }
    stages{
        stage("print"){
            steps{
                git("shubham")

            }
        }
        stage("checkout"){
            steps{
                echo " type name ${git_username}"

            }
        }
    }

}
