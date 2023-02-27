pipeline{
    agent any
stages{
    stage("build") {
        steps {
            echo "building application..."
            sh "javac sashank.java"
        }
    }

    stage("test") {
        steps {
            echo "testing application..."
            sh "java sashank"
        }
    }

    stage("deploy") {
        steps {
            echo "deploying application..."
            sh "java sashank"
        }
    }
}
}
