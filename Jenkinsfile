//Pipeline declarativo siempre se empieza con pipeline{}
pipeline {
    
    //Declaramos el nodo o agente que ejecutara las tareas, en este caso cualquiera disponible
    agent any
    
    //definicion de fases
    stages{
        
        //primera stage
        stage('Stage_1  Build'){
            //definimos los pasos de cada stage
            steps{
                
                echo 'Stage_1 step 1';
            }
        }
        //segunda stage
        stage('Stage_2 - Test'){
            //definimos los pasos de cada stage
            steps{
                
                echo 'Running Unit test....';
                echo 'Running Integracion test....';
                echo 'Running Aceptation test....';
            }
        }
        //tercera stage
        stage('Stage_3 - Deploy'){
            //definimos los pasos de cada stage
            steps{
                
                echo 'Deploying artifact';
            }
        }
        
    }
    
    
}
