# openebs requirements in vm

```sh
python3 -m pip install --user ansible
ansible-playbook -i inventory.yaml -u debian --become --become-user=root -v playbook.yaml
```
