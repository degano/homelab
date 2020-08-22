# Kubernetes on Raspberry Pi
Manage a k3s Kubernetes cluster on Raspberry Pi.

## Installation
Move to the `ansible_setup` directory and use Ansible to install on the Raspberry Pi(s) everything is needed.


## OOB

Grafana credentials:
```
kubectl create secret generic grafana-admin-credentials --from-literal=username=$(bw get username grafana.raspi.hal) --from-literal=password=$(bw get password grafana.raspi.hal)
```