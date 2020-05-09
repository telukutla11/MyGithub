def workspace;
node
{
    stage('Checkout from SCM')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], 
        doGenerateSubmoduleConfigurations: false, 
        extensions: [], 
        submoduleCfg: [], 
        userRemoteConfigs: [[credentialsId: '22870e22-1581-4390-9689-90f78f765df8',
        url: 'https://github.com/telukutla11/MyGithub']]])
        
    }
    stage('Ststic code Analysis')
    {
        echo "Ststic code Analysis"
    }
    stage('Build the code')
    {
        echo "Build the code"
    }
    stage('Testing')
    {
        echo "Testing the code"
    }
    stage('Artyfacts')
    {
        echo "Artyfactory the code "
    }
    stage('Deploye')
    {
        echo "Deploye the code"
    }
    
}
