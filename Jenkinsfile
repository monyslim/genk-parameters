pipeline{
    agent any
    parameters{
        choice(name: "VERSION", choices: ['1.1.0','1.1.1', '1.1.2', '2.1.0'],description:'')
    }
    stages{
        stage("testing"){
            steps{
                echo "works"
            }
        }
    }
}
