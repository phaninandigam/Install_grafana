pipeline
{ 
    agent any
    stages
    {
        stage("Execute grafana"){
            steps{
                sh "sudo ansible-playbook /etc/ansible/Install_grafana/install_grafana.yml"
                
            }            
        }
    }
}
