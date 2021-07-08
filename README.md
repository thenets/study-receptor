# study-receptor

Docs and experiments with [ansible/receptor](https://github.com/ansible/receptor)


```yaml
- me:
    name: Luiz
    internet: True
    ip: 168.45.90.3

- network-public:
    name: public
    internet: True
    ip: 192.168.0.0/16

- network-private:
    name: private
    internet: True
    ip: 192.168.5.0/16

- network-airgap:
    name: airgap
    internet: False
    ip: 192.168.10.0/16
```
