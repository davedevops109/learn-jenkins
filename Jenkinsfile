// pipeline {
//
//   agent {
//     label 'ansible'
//    }
//
//   stages {
//
//     stage('Hello'){
//         steps {
//             echo 'Helo world'
//         }
//     }
//   }
// }

@library('roboshop') _

pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                script {
                    test
                }
            }
        }
    }
}