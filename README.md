Usage
=====
Install requirements by:

    ansible-galaxy install -r requirements

Fill the needed variables for OCP connection:

    ocp_username:
    ocp_password:
    ocp_api_url:

Run the playbook:

    ansible-playbook install-acm.yml