node()
    {
    stage('Cloning Git')
        {
            checkout scm
        }
        
    stage('Install dependencies') 
        {
            nodejs('nodejs') 
            {
                sh 'npm install'
                echo "Modules installed"
            }
        }
    stage('Build') 
    {
        nodejs('nodejs') 
        {
            echo "Build completed"
        }   
    }
}


