# TERRAFORM

**installation**

[Docs](https://spacelift.io/blog/how-to-install-terraform)

>  1. Make sure the system is up-to-date and install these packages which are needed for further steps:

```
sudo apt-get update && sudo apt-get install -y gnupg software-properties-common curl
```
> 2. Next add the Hashicorp GPG key needed by the repository:

```
curl -fsSL https://apt.releases.hashicorp.com/gpg | sudo apt-key add -
```

> 3. Then, add the official repository for HashiCorp for Linux:

```
sudo apt-add-repository "deb [arch=amd64] https://apt.releases.hashicorp.com $(lsb_release -cs) main"
```

> 4. Now that we have added the repo to the list, let’s update to add the relevant repository content:

```
sudo apt-get update
```
> 5. Once update, run this command to install Terraform:

```
sudo apt-get install terraform
```
---
