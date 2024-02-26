pipeline
       {
        agent any
            stages
                 {
                 stage("Git")
                      {
                      steps
                        {
                        git "https://github.com/kpmc123/task-26.git"
                        }
                      }
                        stage("Run")
                            {
                            steps
                               {
                               sh "python3 main.py"
                               sh "java Demo.java"
                               }
                             }
}
 }
  
