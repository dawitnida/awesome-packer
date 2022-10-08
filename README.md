# Awesome Packer [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)


> A curated list of resources on [HashiCorp's Packer](https://www.packer.io)
> Inspired by [@sindresorhus](https://github.com/sindresorhus)' [awesome][sindresorhus] and 
> [awesome-terraform](https://github.com/shuaibiyy/awesome-terraform). 

> Your [contributions](https://github.com/dawitnida/awesome-packer/blob/master/.github/CONTRIBUTING.md) are welcome!


Packer is an open source tool for creating identical machine images for multiple platforms from a single source 
configuration. Packer is lightweight, runs on every major operating system, and is highly performant, creating machine 
images for multiple platforms in parallel. Packer does not replace configuration management like Chef or Puppet. 
In fact, when building images, Packer is able to use tools like Chef or Puppet to install software onto the image.


**_You can see the updates from [@awesome_packer](https://twitter.com/awesome_packer)_**


## Table of Contents

- [Official Resources](#official-resources)
- [Books](#books)
- [Community](#community)
- [Tutorials and Blog Posts](#tutorials-and-blog-posts)
- Libraries
   - Custom Builders
   - Custom Provisioners
   - Custom Post-Processors
   - Custom Wrappers
- Templates
- [Talks](#talks)


## Official Resources

* [Introduction to Packer](https://www.packer.io/intro/)
* [Packer Documentation](https://www.packer.io/docs/)
* [Packer GitHub](https://github.com/hashicorp/packer)
* [Hashicorp Packer Blog](https://www.hashicorp.com/blog/category/packer)


## Books

* [The Packer Book](https://packerbook.com/)
* [AWS SysOps Cookbook (2nd Edition)](https://www.oreilly.com/library/view/aws-sysops-cookbook/9781838550189/) - Creating machine images with Hashicorp's Packer

## Community

* [Racker](https://github.com/aspring/racker) - opinionated Ruby DSL for generating Packer templates
* [Community repository](https://github.com/packer-community) - a suite of Packer plugin repos

## Libraries

### Custom Provisioners

* [deno](https://github.com/dontlaugh/packer-provisioner-deno) - Use [Deno](https://deno.land/) TypeScript or JavaScript for provisioning.
* [cue](https://github.com/dontlaugh/packer-plugin-cue) - Use [CUE](https://cuelang.org/) for data and file rendering during a Packer build.


#### Custom Wrappers

* [python-packer](https://github.com/abhi1693/python-packer) - A Python interface for packer.io (credit [@abhi1693](https://github.com/abhi1693))


## Tutorials and Blog Posts

* [Using GitLab CI/CD Pipelines to Automate your HashiCorp Packer Builds](https://virtualhobbit.com/2020/05/05/using-gitlab-ci-cd-pipelines-to-automate-your-hashicorp-packer-builds/)
* [How to create custom templates with Packer](https://upcloud.com/community/tutorials/upcloud-packer-builder/)


### Beginner Guides

* [Automate AMI Creation](https://devopscube.com/packer-tutorial-for-beginners/)
* [Automation of AMI Creation Using Packer](https://www.talentica.com/blogs/automation-of-ami-creation-using-packer/)
* [Build Your Own EC2 Machine Images with Packer & Ansible on AWS for Immutable AWS Deployments](https://medium.com/devopslinks/build-your-own-ec2-machine-images-with-packer-ansible-on-aws-for-immutable-aws-deployments-f7dbe81934a1)
* [StackExchange: Questions tagged [packer]](https://devops.stackexchange.com/questions/tagged/packer)


### Custom Templates

* [How to Create Custom Templates with Packer](https://upcloud.com/community/tutorials/upcloud-packer-builder/)


### Talks

* [Building Automated Pipelines for Infrastructure Code with Terraform and Packer](https://youtu.be/4uxUScFWzPc)
* [Packer @ Pinterest](https://youtu.be/L-DMwEN_mUk)
* [Using Terraform, Packer, and Ansible Together - Aaron Krauss: DevOps OKC](https://youtu.be/pkEezNSFWtA)
* [Hashicorp Packer Resources][hashicorp-resource-lib]


[sindresorhus]:            <https://github.com/sindresorhus/awesome>
[hashicorp-resource-lib]:  <https://www.hashicorp.com/resources?product=Packer>
