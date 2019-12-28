# Provisioning MongoDB with Ansible

1. copy in the starter code given.

2. Vagrant init to get a vagrant file - configure this vagrant file
  - check the vagrantfile in this project for more notes

3. Create a yml file in the area noted in the synced folder for the vagrant file - make sure it matches the location used.

4. Run a rake spec to find the failures which need to be fixed

5. Install ansible using - may need to install this when you do a vagrant destroy
````
sudo apt-get install software-properties-common
sudo add-apt-repository ppa:ansible/ansible
sudo apt-get update
sudo apt install ansible

````
6. The steps above were so you can **vim** into the /etc/mongod.config file
  - copy the contents of this file

7. Create a file where your playbook is called **mongod.conf** and paste the contents into that file.

8. Change the bind ip to 0.0.0.0 and save 
