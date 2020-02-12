node {
   stage('SCM Checkout'){
    // Clone repo 
	 git: 'https://github.com/vinodmorya90/myapp'
   }
   stage('compile Package'){
	   // Build using maven
	   
	   sh 'mvn package'
   }
 }
