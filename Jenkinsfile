//Declarative Pipeline

pipeline {
    agent any
    
    stages {

        stage('Checkout_teste_multiplo_projeto_2') {
	        steps {
	            sh 'mkdir -p projeto2'
		        dir("projeto2")
                git branch: "main"
                url: 'https://github.com/weversonmachado/teste_multiplo_projeto_2.git'
	        }
	    }
    }
}
