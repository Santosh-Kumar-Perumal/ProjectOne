> ## Create your first Nginx application by integrating Terraform, Ansible and Google cloud platform.
Provision Compute engine VM using Terrafrom.
Install Nginx webserver inside VM using Ansible

Tech Stack used
1.Visual stuido Editor
2.GitHub Repo 
3.Google Cloud
4.Terraform
5.Ansible
6.Nginx Web Servercd



- [ ] Create a GCP project with your desired name and project ID.
- [ ] Attach billing account to the project and enable compute engine API compute.googleapis.com.
- [ ] Configure the project-ID in main.tf project_id argumnet under local block
- [ ] Generate RSA keys using below command and add the public key to the metadata section under compute in GCP console.
- [ ] ssh-keygen -t rsa -f ~/.ssh/ansible -C ansible -b 2048
- [ ] Point the private key in main.tf under local block map to private_key_path argument.
- [ ] Install ansible play book and terraform


[Reference](https://www.youtube.com/watch?v=wVq5fwx1OQU&t=385s)

