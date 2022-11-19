node {
    stage('Clone') {
      git branch: 'main', url: 'https://github.com/Mimo-Git/helloworld.git'
    }
    stage('Build') {
      sh 'javac Main.java '
    }
    stage('Run') {
      sh 'java Main'
    }
}
