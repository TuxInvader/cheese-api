# Cheese API Test

This ansible playbook will deploy an API through NGINX Controller using the Ansible Collection: nginxinc.nginx_controller

1. Install the collection: `ansible-galaxy collection install nginxinc.nginx_controller`
2. Modify the `vars.yaml` to match your controller fqdn and user/password.
3. Run the playbook: `ansible-playbook deploy.yaml`


