pipeline {
    agent any
	
	stages{
	
	  stage1('git pulling') {
	    steps {
	     git credentialsId: 'c399a8d0-2318-4d7c-afd3-83c0444fb0de', url: 'https://github.com/SAHAPRE/Demojenkins.git'
	  }
	  }
	  stage2('script rijnhgvbn') {
	     sh 'sh myscript.sh'
	  }
	
	}
}
