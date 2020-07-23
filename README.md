# testvar

Display the value of a test variable. Used to test overriding variables when running Ansible through different methods.

See https://access.redhat.com/solutions/3606501

## Example Playbook

```ansible
- hosts: servers
  roles:
    - testvar
  vars:
    testvar_my_test_var: "Value set in Playbook"
```

## License

Apache-2.0

## Author Information

Ben Formosa

© 2020 Commonwealth of Australia
