node {
    stage ('Clone'){
     git 'https://github.com/OusmanaTraore/ansible-jenkins-git.git'
    }
    stage ('Ansible'){
        sh 'ansible-playbook -i hosts playbook.yml'
    }
}
