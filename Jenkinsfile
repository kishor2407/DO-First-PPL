pipeline
{
    agent any
    stages {
           stage('Print_Message')
               { steps{ sh 'echo hello_world'} }
            stage('Build')
                {steps{ sh 'echo Build_successful'}}
        
            stage('Test')
                {steps{ sh 'echo Test_successful'}}
        
            stage('Deploy')
                {steps{ sh 'echo Deploy_successful'}}
        
            stage('Validation')
                {steps{ sh 'echo Validation_successful'}}
    }
}
