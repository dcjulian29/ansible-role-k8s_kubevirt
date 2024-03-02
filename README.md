# Ansible Role: k8s_kubevirt

[![Lint](https://github.com/dcjulian29/ansible-role-k8s_kubevirt/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-k8s_kubevirt/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-k8s_kubevirt.svg)](https://github.com/dcjulian29/ansible-role-k8s_kubevirt/issues)

This an Ansible role to install KubeVirt into a kubernetes cluster.

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.k8s_kubevirt
  src: https://github.com/dcjulian29/ansible-role-k8s_kubevirt.git
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
