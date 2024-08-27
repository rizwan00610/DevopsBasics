Devops Project
adding line to check war transfer to ansible-node
adding line to check ansible-playbook
changed ansible module

checking code :
      - name: remove all old images
      shell: docker rmi -f $(docker images -q);
      ignore_errors: yes
