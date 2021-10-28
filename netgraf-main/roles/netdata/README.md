Role Name
=========

A brief description of the role goes here.

## Prerequisites

-   A Netdata Cloud account. [Sign in and create one](https://app.netdata.cloud) if you don't have one already.

## Quickstart

Here's how to run this playbook as quickly as possible.

First, and populate the `hosts` file with the IP addresses for your node(s). If you want, you can use the `hostname`
variable to set the node's name, which appears both on the local Agent dashboard and Netdata Cloud.

```
203.0.113.0   hostname=node-01
203.0.113.1   hostname=node-02 
```

Next, edit the `vars/main.yml` file to change the `claim_token` and `claim_rooms` variables. To find your `claim_token`
and `claim_room`, go to Netdata Cloud, then click on your Space's name in the top navigation, then click on `Manage your
Space`. Click on the `Nodes` tab in the panel that appears, which displays a script with `token` and `room` strings.

Finally, import the role in your main playbook to setup netdata.

When the playbook finishes, you'll see your nodes appear in Netdata Cloud!


License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
