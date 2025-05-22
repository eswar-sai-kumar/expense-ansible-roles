# expense-ansible-roles

Create 4 EC2 instances(ansible,db,backend,frontend) AMI: RHEL-9-DevOps-practice, No key pair                   

Update route53 records (give private IP for backend and db, public IP for frontend)                         

Open superputty and enter ansible public IP address
                          
```
sudo dnf install ansible -y
```                           

```
git clone https://github.com/eswar-sai-kumar/expense-ansible-roles.git
```          

```
cd expense-ansible-roles
```

```
git pull
```

Don't forget to pull changes when pushed to github

```
ansible-playbook db.yaml
```

```
ansible-playbook backend.yaml
```

```
ansible-playbook frontend.yaml
```

```
ansible-playbook dynamic.yaml
```


                              
