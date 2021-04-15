**THIS IS AN EXAMPLE**

# Getting Started with SR Linux

Nokia is providing SR Linux in a publicly available Docker image.
This is a great way to have a running SR Linux instance in just a few minutes.

Assuming a basic Linux machine (min 2 vCPU & 4GB RAM) with Docker installed, run the following command as root (or using `sudo`):

`docker run nokia/srlinux`

This will pull the latest version of SR Linux (21.3.1 as of this writing).
Other SR Linux versions can be specified with <tag>

### Next Steps

* command to verify the image is running
* `sr_cli` via docker exec or ssh (find mgmt IP address)
* srl commands for version, etc.
* links to examples

## Advanced Labs

To try SR Linux with more than one node or even more complex virtual lab environments, check out [ContainerLab](https://containerlab.srlinux.dev/).

ContainerLab is a multi-vendor tool developed to make building networking labs simple and fast.
It's easy to install and there is a growing [catalog](https://containerlab.srlinux.dev/lab-examples/lab-examples/) of pre-built lab topologies.
This example (link) will build a 3-node Clos network using SR Linux nodes and provide cut-and-paste commands for eBGP configuration.
This is a great way to learn basic SR Linux configuration.

