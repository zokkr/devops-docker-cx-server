node("master") {
    stage('Test Jenkinsfile Runner Image') {
        sh 'echo Hello from Jenkins'
        println("Plugin configuration:")
        Jenkins.instance.pluginManager.plugins.each{
            plugin -> println("${plugin.getShortName()}: ${plugin.getVersion()}")
        }
    }
}
