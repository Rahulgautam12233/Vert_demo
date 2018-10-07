node{
   stage('SCM-Checkout'){
     git 'https://github.com/Rahulgautam12233/Vert_demo'
   }
   stage('Compile-Package'){
      sh 'mvn clean'
      sh 'mvn package'
   }
}
