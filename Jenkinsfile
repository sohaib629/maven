pipeline {
  agent any
  environment {
    PATH = '/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/snap/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/snap/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/snap/bin:/root/maven/bin:/usr/lib/jvm/java-8-openjdk-amd64/bin:/root/apache-ant-1.10.5/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/snap/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/snap/bin:/root/maven/bin:/usr/lib/jvm/java-8-openjdk-amd64/bin:/root/apache-ant-1.10.5/bin:/root/apache-tomcat-8.5.39/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/snap/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/snap/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/snap/bin:/root/maven/bin:/usr/lib/jvm/java-8-openjdk-amd64/bin:/root/apache-ant-1.10.5/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/snap/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/snap/bin:/root/maven/bin:/usr/lib/jvm/java-8-openjdk-amd64/bin:/root/apache-ant-1.10.5/bin:/root/apache-tomcat-8.5.39/bin:/root/maven:/usr/local/maven'
    JAVA_HOME = '/usr/lib/jvm/java-8-openjdk-amd64'
  }

  stages {
    stage('Build') {
      steps {
	sh 'mvn install'
      }
    }
  }
}
