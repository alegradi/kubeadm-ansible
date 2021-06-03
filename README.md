# Kubeadm-Ansible

Ansible role to prepare nodes for a kubeadm Kubernetes install.

## Requirements

Ubuntu 18.04 

## Role Variables

```yaml
kubeadm_packages:
  - kubelet=1.20.0-00
  - kubeadm=1.20.0-00
  - kubectl=1.20.0-00
```

## Dependencies
None

## Testing

Molecule testing is provided with the role. I recommend setting up a python virtual environment with version 3.8. I have included `pip_list.txt` that can be used to install the same version of modules I've used when developing and testing the role.

Simple local testing can be done with:
```bash
molecule test
```

## Example Playbook
```yaml
example playbook comes here
```



## License
MIT


## Author
Adam Legradi <https://github.com/alegradi>
