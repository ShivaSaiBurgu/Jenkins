pipeline {
    agent any
    stages {
        stage(Build)
        {
            steps 
            {
                echo "This is Building stage"
            }
        }
         stage(Scan) 
         {
            steps 
            {
                echo "This is scanning stage"
            }
         }
          stage(Test) {
            steps {
                echo "This is testing stage"
            }
          }
    }
}