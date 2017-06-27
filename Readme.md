## DataStax on the AWS Cloud

Current Release: https://github.com/aws-quickstart/quickstart-datastax/releases/tag/v1.0

### Deployment options:

Deploying this Quick Start for a new virtual private cloud (VPC) with default parameters builds the following DataStax Enterprise environment in the AWS Cloud.

### Architecture:
Quick Start DSE architecture on AWS
![quickstart-datastax](/images/datastax.png)

The Quick Start sets up the following:
* One EC2 instance running OpsCenter, the DSE cluster management web console.
* Additional EC2 instances depending on how many DSE ‘datacenters’ and ‘nodes’ are requested, e.g. requesting 3 datacenters with 5 nodes each will create 15 EC2 instances.
* One EBS data volume per node instance deployed.
* Optionally a VPC using the AWS Quick Start VPC templates.

