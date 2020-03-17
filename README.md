# This is super small example on howto install fahclient with Ansible

Just add a list of servers into inventory and play `ansible-playbook -i inventory fah.yml`.

To change the user, see the `fah.yml` file and change username variable. I used this to deploy the client to the servers I manage, those have NVIDIA graphics cards.

That's why if it detects `nvidia-smi` the graphic card folding is also enabled.