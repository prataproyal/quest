
pipeline {
agent any
stages {
stage ('Compile Stage') {
steps {
bat 'mvn clean compile'
}
}
stage ('Testing Stage') {
steps {
bat 'mvn test'
}
}
stage ('packaging Stage') {
steps {
bat 'mvn package'
}
}
}
} 