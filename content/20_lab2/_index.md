+++
title = "Lab 2"
chapter = false
weight = 20
+++

## What you will do in this lab:
Using the provided clouformation template build a taskcat config that uses **psuedo-parameters**

We will use override to inject a `LicenseToken` and dymamically inject `AvailiblityZone` values during testing

- Use taskcat overrides pass inputs into the stack that you do not want in the project_root/gitrepo _(secrets like `LicenseKeys` or `APITokens`, etc)_

- Use the **psuedo-parameters** can be used to inject region specfic value _(like `AvailiblityZones` `KeyPairNames` `AccessCIDRs`, etc)_


Hint: Consider cfn_project under **start/lab2** as the root of your Cloudformation project
