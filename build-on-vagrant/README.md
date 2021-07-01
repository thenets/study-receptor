# study-receptor

## Requirements

- Ansible
- Vagrant

## Commands

```bash
# Create VM with Receptor builded
# > Receptor binary will be located at:
# > /vagrant/receptor/receptor
make create

# Rebuild receptor
make rebuild

# Run tests
make test

# Destroy VM and cleanup dirs
make clean
```
