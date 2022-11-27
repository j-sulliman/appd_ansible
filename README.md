# appd_ansible

Uses the Ansible URI to make REST API calls to the AppD Controller

Update "all.yml" under the group_vars directory with your credentials and application IDs and configuration templates to be posted to the REST interface.

This playbook supports:
 * Health Rule Creation
 * Actions
 * Health Rule Policies

List of applications configuration to be deployed to under group_vars/all.yml

This provides a starting template for further configuration and testing.

Having installed ansible, run the playbook as below:

``
ansible-playbook Playbook_AppD_Health_Rules.yml
``

## Demo
https://youtu.be/I733sf1CmM4



## Reference:
 * AppDynamics API Documentation[https://docs.appdynamics.com/appd/22.x/latest/en/extend-appdynamics/appdynamics-apis]