# Ansible Project for the AWS Cloudformation Exercise
This Ansible project was created for, and is therefore heavily dependant on,
[aws-cloudformation-exercise](https://github.com/gliech/aws-cloudformation-exercise).

The project puts some SSH public keys on a number of EC2 instances, configures
the SSH daemon on one to accept external connections, using these keys, and
installs a webserver with Wordpress on others.

But the main focus of this project lays on the exchange of information between
the Cloudformation stack and Ansible, as well as the dynamic filtering of hosts
in the site.yml. The roles used here are neither complete nor secure and are
meant for demonstration purposes only!
