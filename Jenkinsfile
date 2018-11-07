node {
  // Adds timestamps to the output logged by steps inside the wrapper.
  timestamps{
    stage("pull from github"){
      git credentialsId: '6f410cb8-2df4-4438-9dc9-3c52b9edeaf6', url: 'https://github.com/gsm23/cloudformation.git'
    }
    stage("List the files pulled"){
      sh "ls -l ."
    }
  }
}
