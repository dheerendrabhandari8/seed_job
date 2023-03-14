job('new_example') {
/*  
  scm {
   github('bhanukumari/jenlkins-role', 'main')
    }
  */
  scm {
  git {
    remote {
      url 'https://github.com/bhanukumari/jenlkins-role.git'
    }

    branch 'main'
  
  steps {
        wrappers {
          sshAgent('bhanu')
    
 ansiblePlaybook('jenkins.yml') {
      inventoryPath('hosts')
   // hostKeyChecking(false)
    }
  }
  }
  }
  }
}
