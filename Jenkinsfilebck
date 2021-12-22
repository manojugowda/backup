pipeline{
   agent { label 'master' }
   stages{
	   	   stage('backup'){
        steps{
	sh 'scp -r /var/lib/jenkins root@172.31.1.117:/home/ubuntu'
    }
   }
  }
 }
