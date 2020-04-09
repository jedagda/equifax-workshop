# Development environment

 # Requirements: 
- Virtualbox 6.* <br/>
- Vagrant
- git

# Steps to follow:
 1. Clone this repo into your host machine by running: <br/>
    - git clone https://github.com/jedagda/equifax-workshop.git
 
 2. Once you have cloned the repo and once inside the directory with the vagrantfile run: <br/>
    - `vagrant up`

 3. Let the script finish and the open virtualbox and you will see your newly created vm running.  <br/>

 2. To log into the virtual machine using the following credentials: <br/>
    - `username: vagrant`
    - `password: vagrant`

3. Once logged-in, run the provisioning script: <br/>\
    - `cd setup`
    - `sudo ./wrkshp-dev-env.sh`

4. Once the script has finished run execute the following command: <br/>

    - `sudo shutdown now -r`

5. Start your vm as you normally would and use the same credentials to login



