node{ 

stage('cloning repo'){
  checkout scm
}

stage('Build'){
  sh 'sudo su -'
  sh 'sudo docker build -t test:2.4 .'
  sh 'sudo docker run -it -d --name dctest -p 80:80 test:2.4'
}
  
 
  
}
