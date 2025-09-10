pipeline {

agent {
label 'slaves'
}

stages {
   
   stage('checkout') {
        
		steps {
		cleanWs()
		echo "this is stage1"
		}
   
   }
   
   stage('Build') {
        
		steps {
		echo "this is stage2"
		}
   
   }
   stage('SonarQube') {
        
		steps {
		echo "this is stage3"
		}
   
   }
   stage('Uploadto nexus') {
        
		steps {
		echo "this is stage4"
		}
   
   }
   stage('Deploytotomcat') {
        
		steps {
		echo "this is stage5"
		}
   
   }

}

}
