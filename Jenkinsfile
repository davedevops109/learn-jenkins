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

@Library('roboshop') _

pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                script {
                    def abc = "Hello"
                    def xyz = 10

                    print "abc = ${abc}"
                    print "xyz = ${xyz}"

                    print abc
                }
            }
        }
    }
}