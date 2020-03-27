node {
    stage ('Clone'){
     git 'https://github.com/OusmanaTraore/ansible-jenkins.git'
    }
    stage ('Ansible'){
        ansible-playbook {
            colorized: true,
            become: true,
            playbook: 'playbook.yml',
            inventory: 'hosts.yml'
        }
    }
}
