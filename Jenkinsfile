node {
    stage ('Clone'){
     git 'https://github.com/OusmanaTraore/ansible-jenkins.git'
    }
    stage ('Ansible') {
        ansiblePlaybook (
            colorized: true ,
            become: true ,
            playbook: 'playbook.yml',
            inventory: 'inventory.yml'
        )
    }
}
