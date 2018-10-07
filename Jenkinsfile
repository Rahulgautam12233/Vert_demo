node{
   stage('SCM-Checkout'){
     git 'https://github.com/Rahulgautam12233/Vert_demo'
   }
   stage('Compile-Package'){
     sh '/opt/apache-maven-3.5.4/bin/mvn package'
   }
}
