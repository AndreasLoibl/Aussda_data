dir('/tmp') {
    // some block
    git credentialsId: '252a5a19-548e-4d51-94e1-15646223542a', url: 'https://github.com/AndreasLoibl/Aussda_data/'
}


sh label: '', script: '''export CLASSPATH=".:selenium-server-standalone.jar:testng-6.8.7.jar"
cd /tmp
javac simpleAUSSDA.java
java  simpleAUSSDA
'''
