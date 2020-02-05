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
- Templates
- Talks


## Official Resources

* [Introduction to Packer](https://www.packer.io/intro/)
* [Packer Documentation](https://www.packer.io/docs/)
* [Packer GitHub](https://github.com/hashicorp/packer)
* [Hashicorp Packer Blog](https://www.hashicorp.com/blog/category/packer)


## Books

* [The Packer Book](https://packerbook.com/)

## Community

* [Racker](https://github.com/aspring/racker) - opinionated Ruby DSL for generating Packer templates

## Libraries

### Custom Provisioners

* [deno](https://github.com/dontlaugh/packer-provisioner-deno) - Use [Deno](https://deno.land/) TypeScript or JavaScript for provisioning.


## Tutorials and Blog Posts

### Beginner Guides

* [Automate AMI Creation](https://devopscube.com/packer-tutorial-for-beginners/)
* [Automation of AMI Creation Using Packer](https://www.talentica.com/blogs/automation-of-ami-creation-using-packer/)
* [Build Your Own EC2 Machine Images with Packer & Ansible on AWS for Immutable AWS Deployments](https://medium.com/devopslinks/build-your-own-ec2-machine-images-with-packer-ansible-on-aws-for-immutable-aws-deployments-f7dbe81934a1)


### Custom Templates

* [How to Create Custom Templates with Packer](https://upcloud.com/community/tutorials/upcloud-packer-builder/)


[sindresorhus]: <https://github.com/sindresorhus/awesome>
