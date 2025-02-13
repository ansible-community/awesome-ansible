# Awesome Ansible [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<!--lint disable double-link-->
[<img src="ansible_logo.svg" align="right" width="90">](https://www.ansible.com/)

This is a collaborative community curated list of awesome Ansible resources, tools, Roles, tutorials and other related stuff.

[Ansible](https://www.ansible.com/) is an open source toolkit, written in Python, it is used for  configuration management, application deployment, continuous delivery, IT infrastructure automation and automation in general.

:warning: Before editing the list to add your project, take a look at the [Ansible ecosystem project development resources](https://docs.ansible.com/ansible/devel/community/ecosystem_project_resources.html). Let's make sure our users, contributors, and maintainers have the best possible experience!

<!--lint enable double-link-->
<!--lint disable-->

## Contents

- [Awesome Ansible ](#awesome-ansible-)
  - [Contents](#contents)
  - [Official resources](#official-resources)
  - [Community](#community)
  - [Tutorials](#tutorials)
  - [Books](#books)
  - [Videos](#videos)
  - [Tools](#tools)
  - [Blog posts and opinions](#blog-posts-and-opinions)
    - [German](#german)
    - [French](#french)
  - [Playbooks, Roles and Collections](#playbooks-roles-and-collections)
  - [Editor and IDE Integrations](#editor-and-ide-integrations)

<!--lint enable-->

## Official resources

> Official resources by and for Ansible.

- [Latest Ansible Documentation](https://docs.ansible.com/ansible/latest/user_guide/index.html) - Latest user guide and documentation for Ansible.
- [Ansible Galaxy Website](https://galaxy.ansible.com/) - Official repository and community site for Ansible Roles.
- [Ansible Blog](https://www.ansible.com/blog) - Official Ansible blog.

## Community

Join the Ansible forum:

<!--lint disable double-link-->
- [Get Help](https://forum.ansible.com/c/help/6) - Get help or help others. Please add appropriate tags if you start new discussions.
- [Bullhorn newsletter](https://docs.ansible.com/ansible/devel/community/communication.html#the-bullhorn) - Used to announce releases and important changes.
- [Social Spaces](https://forum.ansible.com/c/chat/4) - Gather and interact with fellow enthusiasts.
- [News & Announcements](https://forum.ansible.com/c/news/5) - Track project-wide announcements including social events.

For more information about communication, see the [Ansible communication guide](https://docs.ansible.com/ansible/devel/community/communication.html).
<!--lint enable double-link-->

## Tutorials

> Tutorials and courses to learn Ansible.

- [How To Manage Remote Servers with Ansible](https://www.digitalocean.com/community/tutorial_series/how-to-manage-remote-servers-with-ansible) - This Tutorial goes over how to use Ansible to manage remote servers.
- [Ansible Tutorial by leucos](https://github.com/leucos/ansible-tuto) - 12 Step Tutorial for Ansible.
- [Programming Community Curated Resources for learning Ansible](https://hackr.io/tutorials/learn-ansible) - A list of recommended resources.
- [Ansible TopTechSkills.com Tutorial Series on Ansible](https://www.toptechskills.com/ansible-tutorials-courses/) - Tutorials on how to Install and use Ansible.
- [Official Ansible labs by Red Hat](https://ansible.github.io/workshops/exercises/ansible_rhel/) - Training Course for Ansible Automation Platform.
- [Ansible Tutorials on DigitalOcean](https://www.digitalocean.com/community/tags/ansible?subtype=tutorial) - Basic tutorials on DigitalOcean.com.
- [Ansible Tutorial by BlueBanquise team](http://bluebanquise.com/documentation/releases/1.5.0/training_ansible.html) - Basic Ansible tutorial.
- [Ansible Tutorial for Beginners: Playbook & Examples](https://spacelift.io/blog/ansible-tutorial) - Introduction to Ansible for beginners.
- [Ansible Tutorials for Beginners and Advanced](https://ansible.puzzle.ch/) - Workshop on multiple topics with different levels of difficulty.
- [Ansible For DevOps](https://github.com/geerlingguy/ansible-for-devops) - This repository contains Ansible examples developed to support different sections of `Ansible for DevOps` by Jeff Geerling, which is listed in the following section of books about Ansible.

## Books

> Books about Ansible.

- [Ansible for DevOps](https://www.ansiblefordevops.com/) - This book helps to start using Ansible to provision and manage anywhere from one to thousands of servers. Free sample can be read [here](https://leanpub.com/ansible-for-devops/read_sample).
- [Ansible for Kubernetes](https://www.ansibleforkubernetes.com/) - Deploy and maintain real-world massively-scalable and high-available applications with Ansible.
- [How To Manage Remote Servers with Ansible eBook](https://www.digitalocean.com/community/books/how-to-manage-remote-servers-with-ansible-ebook) - This book is based on the "How To Manage Remote Servers with Ansible" tutorial series.
- [The Tao of Ansible: Mastering Automation with Simplicity and Grace](https://www.amazon.co.uk/Tao-Ansible-Mastering-Automation-Simplicity/dp/B0DTTTM3XG) - A guide to Ansible that emphasizes simplicity, elegance, and the philosophy of automation without complexity.

## Videos

> Video tutorials and Ansible training.

- [Ansible YouTube Channel](https://www.youtube.com/channel/UCPJo5UY1KsP7J1BuHmiWNzQ) - Official Ansible YouTube channel.
- [Introduction to Ansible](https://youtu.be/iVWmbStE1MM) - Introduction to Ansible by Cloud Academy.
- [Ansible 101 by Jeff Geerling](https://www.jeffgeerling.com/blog/2020/ansible-101-jeff-geerling-youtube-streaming-series) - Great video series on Ansible, by Jeff Geerling.
- [Ansible TopTechSkills.com Tutorial Series on YouTube](https://www.youtube.com/playlist?list=PLMyOob-UkeytIleCbMlFfCzaunOh27hm6) - Video tutorials on Ansible.
- [Ansible Essentials - Course](https://www.redhat.com/en/services/training/do007-ansible-essentials-simplicity-automation-technical-overview) - Free Video Classroom on Ansible essentials by Red Hat.
- [Complete Ansible Course 2020 by DevOps Journey](https://www.youtube.com/watch?v=KuiAiUyuDY4&list=PLnFWJCugpwfzTlIJ-JtuATD2MBBD7_m3u&index=1) - Free Video Course on Ansible including labs to follow along.
- [Getting started with Ansible](https://youtube.com/playlist?list=PLT98CRl2KxKEUHie1m24-wkyHpEsa4Y70) - YouTube tutorial series by LearnLinuxTV.

## Tools

> Tools for and using Ansible.

- [Automation Controller](https://www.ansible.com/products/controller) - Automation Controller (formerly Ansible Tower) by Red Hat helps you scale IT automation, manage complex deployments and speed productivity. Extend the power of Ansible to your entire team.
- [AWX](https://github.com/ansible/awx) - AWX provides a web-based user interface, REST API, and task engine built on top of Ansible. It is the upstream project for Automation Controller, a commercial derivative of AWX.
- [Ansible Lint](https://github.com/ansible/ansible-lint) - Checks Playbooks for best practices and behavior that could potentially be improved.
- [Ansible Doctor](https://github.com/thegeeklab/ansible-doctor) - Simple annotation like documentation generator for Ansible roles based on Jinja2 templates.
- [Ansible cmdb](https://github.com/fboender/ansible-cmdb) - Takes the output of Ansible's fact gathering and converts it into a static HTML page.
- [ARA](https://github.com/ansible-community/ara) - ARA Records Ansible playbooks and makes them easier to understand and troubleshoot with a reporting API, UI and CLI.
- [Ansible Inventory Grapher](https://github.com/willthames/ansible-inventory-grapher) - Displays inventory inheritance hierarchies and the level at which variables are defined in an inventory.
- [Mitogen for Ansible](https://mitogen.networkgenomics.com/ansible_detailed.html) - Speed up Ansible substantially with Mitogen.
- [Molecule](https://molecule.readthedocs.io/en/latest/) - Molecule aids in the development and testing of Ansible roles.
- [Packer Ansible Provisioner](https://www.packer.io/plugins/provisioners/ansible/ansible-local) - This Provisioner can be used to automate VM Image creation via Packer with Ansible.
- [Excel Ansible Inventory](https://github.com/KeyboardInterrupt/ansible_xlsx_inventory) - Turn any Excel Spreadsheet into an Ansible Inventory.
- [terraform.py](https://github.com/mantl/terraform.py) - Ansible dynamic inventory script for parsing Terraform state files.
- [ansible-navigator](https://github.com/ansible/ansible-navigator) - A text-based user interface (TUI) for Ansible.
- [squest](https://hewlettpackard.github.io/squest/) - Self-service portal for Automation Controller job templates.
- [ansible-bender](https://ansible-community.github.io/ansible-bender/build/html/index.html) - Tool which bends containers using Ansible playbooks and turns them into container images.
- [ansible-runner](https://github.com/ansible/ansible-runner) - A tool and python library that helps when interfacing with Ansible directly or as part of another system whether that be through a container image interface, as a standalone tool, or as a Python module that can be imported.
- [ansible-builder](https://ansible-builder.readthedocs.io/en/latest/) - Using Ansible content that depends on non-default dependencies can be tricky. Packages must be installed on each node, play nicely with other software installed on the host system, and be kept in sync.
- [kics](https://github.com/Checkmarx/kics) - SAST Tool that scans your ansible infrastructure as code playbooks for security vulnerabilities, compliance issues and misconfigurations.
- [php-ansible Library](https://github.com/maschmann/php-ansible) - OOP-Wrapper for Ansible, making Ansible available in PHP.
- [TD4A](https://github.com/cidrblock/td4a) - Design aid for building and testing jinja2 templates, combines data in yaml format with a jinja2 template and render the output.
- [Ansible Playbook Grapher](https://github.com/haidaraM/ansible-playbook-grapher) - Command line tool to create a graph representing your Ansible playbook plays, tasks and roles.
- [ansible-doc-extractor](https://github.com/xlab-steampunk/ansible-doc-extractor) - A tool that extracts documentation from Ansible modules in the HTML form.
- [Ansible Semaphore](https://github.com/ansible-semaphore/semaphore) - Ansible Semaphore is a modern UI for Ansible.
- [Steampunk Spotter](https://steampunk.si/spotter/) - Provides an Assisted Automation Writing tool that analyzes and offers recommendations for your Ansible Playbooks.
- [ansible-roster](https://gitlab.com/jlecomte/ansible/ansible-roster) - Ansible Roster inventory plugin to generate inventory from a host oriented yaml file. Supports ranges, regex hostnames, file inclusions, and variable merging.
- [Monkeyble](https://hewlettpackard.github.io/monkeyble/) - A callback plugin that allow to execute end-to-end tests on playbooks with a Pythonic testing and CI/CD approach to detect regressions.
- [aar-doc - Automated Ansible Role Documentation](https://github.com/telekom-mms/Automated-Ansible-Role-Documentation) - Generate documentation automatically from an Ansible role's metadata.
- [antsichaut](https://github.com/ansible-community/antsichaut) - Automate the filling of a changelog.yaml used by antsibull-changelog.
- [ansibledb](https://github.com/nbentoumi/ansibledb) - Flask API Web server that uses MongoDB as database to store Ansible reports and facts; this tool can be used to query hosts and facters managed Ansible as well search Ansible logs.
- [Ansible Template Playground](https://tech-playground.com/playgrounds/ansible-template/) - Online playground for running, testing and sharing Ansible templates.

## Blog posts and opinions

> Best practices and other opinions on Ansible.

- [Ansible (Real Life) Good Practices](https://reinteractive.com/posts/167-ansible-real-life-good-practices) - Best practice guidelines.
- [Testing Ansible Roles Against Windows with Test-Kitchen](https://hodgkins.io/testing-ansible-roles-windows-test-kitchen) - Using Test-Kitchen with Ansible to apply playbooks to Windows machines and test them with [Pester](https://github.com/pester/Pester/).
- [Ansible Best Practices by AndiDog](https://andidog.de/blog/2017-04-24-ansible-best-practices) - Practices covering many aspects of an Ansible setup, including hints to support different environments (testing, staging, production).
- [Getting started with Ansible](https://steampunk.si/blog/getting-started-with-ansible/) - Introduces Ansible, provides installation instructions and gives an interactive walkthrough of Ansible's basic functionalities, like running Ansible playbooks and installing Ansible content.
- [Taking Ansible apart](https://steampunk.si/blog/taking-ansible-apart/) - Describes and shows how most commonly used Ansible components work.
- [Enhancing Ansible Development with SOLID Principles](https://github.com/kksat/SOLID-Ansible) - Discover how the fundamental principles of SOLID—Single Responsibility, Open-Closed, Liskov Substitution, Interface Segregation, and Dependency Inversion—can significantly elevate your Ansible role and playbook development.

### German

- [Ansible – Was ich am Ad-hoc-Modus schätze](https://www.my-it-brain.de/wordpress/ansible-was-ich-am-ad-hoc-modus-schaetze/) - Opinion what the author likes about the Ansible Ad-Hoc mode.

### French

- [Apprendre et Maitriser Ansible l'outil de gestion de configuration](https://blog.stephane-robert.info/post/introduction-ansible/) - A large of courses on Ansible in French.

## Playbooks, Roles and Collections

> Awesome production ready Playbooks, Roles and Collections to get you up and running.

- [Ansible Vagrant Examples by geerlingguy](https://github.com/geerlingguy/ansible-vagrant-examples) - Ansible examples using Vagrant to deploy to local VMs.
- [Ansible playbook for Linux machine setup](https://github.com/olivomarco/my-ansible-linux-setup) - Ansible playbook for setting up a self-updating, hardened Debian/Ubuntu machine with Docker daemon.
- [Ansible Lockdown](https://github.com/ansible-lockdown) - Ansible content to assist in both auditing and remediating against [CIS](https://www.cisecurity.org/#/) or [STIG](https://public.cyber.mil/stigs/) baseline compliance for OS's and Applications.
- [DevSec Hardening Framework](https://dev-sec.io/) - The DevSec collection helps you harden your Linux Based OS as well as MySQL, NGINX and SSH Server/Services.
- [T.A.D.S. boilerplate](https://github.com/Thomvaill/tads-boilerplate) - Provision and deploy a Docker Swarm cluster to development environment and to production. Infrastructure as Code and DevOps best practices.
- [Openstack Ansible](https://github.com/openstack/openstack-ansible) - Ansible Playbooks for deploying [OpenStack](https://www.openstack.org/).
- [Robert de Bock](https://robertdebock.nl) - A extensive collection of Ansible roles.
- [DebOps](https://docs.debops.org/en/master/) - A extensive collection of Debian based Ansible Playbooks.
- [ansible-ssm](https://github.com/HQarroum/ansible-ssm) - An ansible role to provision physical and virtual hosts with the AWS SSM agent.
- [BlueBanquise](https://github.com/bluebanquise/bluebanquise) - An ansible coherent roles collection to deploy clusters.
- [redhat-cop](https://github.com/search?q=topic%3Aansible+org%3Aredhat-cop&type=Repositories&s=updated&o=desc) - Repositories with ansible topic of the Red Hat Communities of Practice project.

## Editor and IDE Integrations

> Awesome Integrations into Text Editors and IDE's to make development with/for Ansible easier.

- [Ansible Language Server](https://github.com/ansible/ansible-language-server) - Language Server that adds support for Ansible, to compatible Editors.
- [VS Code - official Ansible Extension](https://marketplace.visualstudio.com/items?itemName=redhat.ansible) - Adds language support for Ansible to Visual Studio Code and OpenVSX compatible editors by leveraging ansible-language-server.
<!--lint disable -->
- [Vim](https://www.vim.org/) - An open-source, free command-line text editor. Useful Vim plugins include:
  - [Ansible vim](https://github.com/pearofducks/ansible-vim) - A vim syntax plugin for Ansible 2.x, it supports YAML playbooks, Jinja2 templates, and Ansible's hosts files.
  - [Ansible vim and neovim plugin](https://www.npmjs.com/package/@yaegassy/coc-ansible) - A vim plugin (lsp client) for Ansible, it supports autocompletion, syntax highlighting, hover, diagnostics, and goto support.
- [Emacs](https://www.gnu.org/software/emacs/) - A free, open-source text editor and IDE that supports auto-indentation, syntax highlighting and a built in terminal shell (among other things):
  - [lsp-mode](https://emacs-lsp.github.io/lsp-mode/page/lsp-ansible/) - Ansible Language Server Protocol support for Emacs: provides syntax highlighting, auto-completion and diagnostics.
  - [yaml-mode](https://github.com/yoshiki/yaml-mode) - YAML highlighting and syntax checking.
  - [jinja2-mode](https://github.com/paradoxxxzero/jinja2-mode) - Jinja2 highlighting and syntax checking.
  - [magit-mode](https://github.com/magit/magit) - Git porcelain within Emacs.
  - [flymake-ansible-lint](https://github.com/jamescherti/flymake-ansible-lint.el) - Ansible Lint integration with automatic/continuous annotation of errors, warnings, and info while editing.
- [PyCharm](https://www.jetbrains.com/pycharm/) - A full IDE for Python software development. Useful plugins include:
  - [Ansible Lint](https://plugins.jetbrains.com/plugin/20905-ansible-lint) - Ansible Lint integration with automatic/continuous annotation of errors, warnings, and info while editing.
  - [Ansible Vault Integration](https://plugins.jetbrains.com/plugin/14353-ansible-vault-integration) - Ansible vault integration for IntelliJ IDEA with context actions for vaulting and unvaulting secrets.
<!--lint enable -->
