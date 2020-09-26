pipeline{
   agent  { label 'jenkinsSlave1' } 
   stages {
       stage("Build"){
	        steps {
			    echo "Hello build section !"
			}
	   }
	   stage("Test"){
	        steps {
			    echo "Hello test section !"
			}
	   }
	   stage("Deploy"){
	        steps {
			    echo "Hello deploy section !"
			}
	   }
   }
}
