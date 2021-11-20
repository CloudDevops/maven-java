node{
	stage('SCM checkout'){
	git 'git@github.com:CloudDevops/maven-java.git'
	}
	stage('Compile'){
	sh '/opt/homebrew/bin/mvn compile'
	}
}
