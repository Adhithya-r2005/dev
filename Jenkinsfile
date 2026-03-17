pipeline{
  agent any
  stages {
    
    stage('Clone'){
      steps{
        git url: "https://github.com/Adhithya-r2005/dev.git",
          branch:"main"
      }
    }
  stage('Run Script') {
    steps {
     sh 'chmod +x script.sh'
     sh './script.sh'
    }
  }
  }
}







sudo apt update
sudo apt install openjdk-21-jdk -y
sudo rm jenkins.war
sudo rm -rf ~/.Jenkins
wget https://get.jenkins.io/war-stable/latest/jenkins.war
java -jar jenkins.war --httpPort=8080
 http://loacalhost:8080 #GO TO WEB
hostname -I //
copy tht id and paste in jenkin we site

then give username and pass

then go to GitHub create a new repo
simple-jenkins-demo

create a Jenkinsfile

pipeline{
  agent any
  stages {
    
    stage('Clone'){
      steps{
        git url: "https://github.com/Adhithya-r2005/simple-jenkins-demo.git",
          branch:"main"
      }
    }
  stage('Run Script') {
    steps {
     sh 'chmod +x script.sh'
     sh './script.sh'
    }
  }
  }
}



create another file

#! /bin /bash
echo "hi bro wtsup"


now Jenkins > new items > simple-jenkins-demo > done

pipeline scm>git and in repo>copy thr repo url>change branch specifier to main


then done >click build now



open one more terminal then
if 
ngrok --version

is not installd
sudo apt update
sudo apt install snapd -y
sudo snap install ngrok


then login to ngrok
copy the token displayed in dashboard
paste that in the terminal

ngrok http 8080

u get a forwarding link copy that 


and go to git hub>setting>webhook>add>for that url paste the terminal link
followed by /github-webhook/

content type application/jason>then add



then go to Jenkins trigger click
GitHub hook trigger for gitscm olling>done



thats it u create new file followed by echo "">comm
then in Jenkins it auto builds



extra for modification


pipeline{
agent any

stages{

stage('Clone'){
steps{
git url: "https://github.com/usernameislol12/program3.git", branch:"main"
}
}

stage('Run Script'){
steps{
sh 'chmod +x script.sh'
sh './script.sh'
}
}

stage('Check Python'){
steps{
sh 'python3 --version'
}
}

stage('Run Python File'){
steps{
sh 'python3 app.py'
}
}

}
}
