# asdf-openshift-install

![CI](https://github.com/hhemied/asdf-openshift-install/workflows/CI/badge.svg?branch=main)

[OpenShift-installer CLI](https://github.com/openshift/installer) (openshift-install) plugin for [asdf](https://github.com/asdf-vm/asdf) version manager.

## Install

```bash
asdf plugin add openshift-install https://github.com/hhemied/asdf-openshift-install.git
```

### List all available versions to install

```basn
asdf list all openshift-install
```

### Install the latest stable version

```bash
asdf install openshift-install stable
```

### Install the latest and greatest version

```bash
asdf install openshift-install latest
```

### Install specific version

```bash
asdf install openshift-install stable-4.10
```

### Activate a specific version for the current running session

```bash
asdf shell openshift-install stable-4.10
```

### Activate a specific version for the current shell.

```bash
asdf global openshift-install stable-4.10
```

## For more details on how to use, please visit [asdf-vm](https://asdf-vm.com/) website

Check the [asdf](https://github.com/asdf-vm/asdf) README for instructions on how to install and manage versions of openshift-install.
