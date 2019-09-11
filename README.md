# SUSE Eirini bits

This repository is the collection of all the needed task definitions and pipelines needed, in order to build the Eirini bits for a SUSE flavor or Eirini (https://github.com/cloudfoundry-incubator/eirini)

## Bits

- eirinifs
  This is the "stack" on which the application workloads run. Equivalent to the sle15 and cflinuxfs3 stacks in diego deployments of CloudFoundry.
- sshd (https://github.com/cloudfoundry/diego-ssh/tree/master/cmd/sshd)
  This is the same ssh daemon that runs inside the application container in a diego deployment of CloudFoundry. This is included in the eirinifs in order to enable the `cf ssh` feature in Eirini deployments.

TODO:
- downloader/executor/uploader images from eirini-staging.
