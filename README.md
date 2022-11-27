# appd_ansible

Uses the Ansible URI to make REST API calls to the AppD Controller

Update "all.yml" under the group_vars directory with your credentials and application IDs.

This playbook supports:
 * Health Rule Creation
 * Actions
 * Health Rule Policies

Health rules, actions and policy configuration is defined in health_rule.json email_actions.json and hr_action_policy.json respectively.

List of applications configuration to be deployed to under group_vars/all.yml

This provides a starting template for further configuration and testing.

Having installed ansible, run the playbook as below:

``
ansible-playbook Playbook_AppD_Health_Rules.yml
``

## Demo
https://youtu.be/I733sf1CmM4

