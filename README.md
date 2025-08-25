# uds-rke2-demo

This repo provides configuration and automation for deploying UDS Core on RKE2 with an emphasis on on-prem installations. The code in this repo is meant to accompany the official UDS docs.


## Quickstart (using Lima)

This quickstart is for users who want to deploy UDS RKE2 on a local Ubuntu VM using Lima.

### Host System requirements

The following requirements assume you will be running a VM locally using Lima

- 32GB RAM
- 14 CPU cores


### Prerequisites

- [Lima](https://lima-vm.io/docs/installation/)
- [UDS CLI](https://github.com/defenseunicorns/uds-cli/tree/main?tab=readme-ov-file#install)


The following command runs the `default` task in the [tasks.yaml](https://github.com/defenseunicorns-labs/uds-rke2-demo/blob/main/tasks.yaml) file in this repo to create a Lima Ubuntu VM with an RKE2 cluster, and installs UDS Core:

```
uds run
```


## Quickstart (RKE2 already running)

This quickstart assumes an RKE2 cluster is running and is accessible via the CLI.

### System Requirements

The following are recommended compute requirements for the system that RKE2 is running on:

- 20GB RAM
- 10 CPU cores

### Prerequisites

- [UDS CLI](https://github.com/defenseunicorns/uds-cli/tree/main?tab=readme-ov-file#install)

Assuming you are connected to the RKE2 cluster, the following command will install UDS Core and and its prerequisites

```
uds run install
```

## Further reading

:construction: will eventually link to UDS docs site :construction:
