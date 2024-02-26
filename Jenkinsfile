pipeline
       {
        agent any
            stages
                 {
                 stage("Git")
                      {
                      steps
                        {
                        git "https://github.com/kpmc123/jenkins_practice.git"
                        }
                      }
                        stage("Run")
                            {
                            steps
                               {
                               sh "python3 main.py"
                               sh "java demo.java"
                               }
                             }
}
 }
  
